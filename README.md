# Real_Time_Face_Expression_Detection
## OverView
It is a face expression detectection model that can be used to identify a person's real time emotion. 
The model can identify 7 kinds of emotion.<br/>
Sad<br/>
Angry<br/>
Disgust<br/>
Fear<br/>
Happy<br/>
Neutral<br/>
Surprise

## Note-
To avoid error, Please download "haarcascade_frontalface_default.xml" from opencv github profile.<br/>
If you want to use this model then download "Real Time Face Expression" & "faceExprssion" files from my github and run on your computer.

## Data Resource
https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset#images.zip

## Dependencies
Jupyter Notebook

### Packeges
tensorflow<br/>
numpy<br/>
matplotlib<br/>
opencv<br/>
pickle<br/>
random<br/>
os<br/>
time

### Data Preprocessing
 We've got the data, but we can't exactly just stuff raw images right through our convolutional neural network. <br/> 
 we need all of the images to be the same size, and then we also will probably want to just grayscale them.<br/>
 Also, the labels of all the expressions are not useful, we want them to be one-hot arrays.
 
 ### Normalized image size
 60*60
 
 ## Model
 ### Convolutional Neural Network
 Training Set= 25938 Samples<br/>
 Validation Set= 2883 Samples
 
 ### Activation Functions
1.Relu<br/>
2.Softmax
 
 ### Optimizer 
 Adam<br/>
 Batch Size=32<br/>
 Epochs=50
