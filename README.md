# Machine-Learning-Projects
Repo for aggregating my Machine Learning projects in Keras/Tensorflow. Will be expanded as I continue to produce work.

## Keras ANN Handwriting Recognition Model
![alt text](imgs/handwriting.PNG)
![alt text](imgs/ANN_accuracy.PNG)  
The first model to be added to my repo. This sequential ANN model built in Keras analyzes human handwriting, specifically
numbers from 0-9 and labels them accordingly with a ~98% accuracy rate. This model essentially works by feeding a 768-bit bitstream into a series of nodes which use continually updating weights to try and find the best combination. This leads the model to be incapable of things like analyzing a 3x3 block and realizing that a C-like arrangement of pixels may be a curve etc. Essentially, this cannot detect features but with that in mind, it still produces fairly impressive accuracy.

## Keras CNN Handwriting Recognition Model
![alt text](https://adeshpande3.github.io/assets/Cover.png)  
![alt text](imgs/CNN_accuracy.PNG)  
This model differs from the ANN version in that we analyze the image in the form of 3x3 filters. This approach which allows for receptive fields grants the model the ability to identify features such as edges and curves, which is not possible in a 768-bit bitstream as used in the ANN.

This model is more accurate and capable but substantially slower.
