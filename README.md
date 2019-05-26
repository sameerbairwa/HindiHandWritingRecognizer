# HindiHnadWritingRecognizer
This code helps you classify different alphabets of hindi language (Devanagiri) using Convnets</br>
<h3>Description</h3>
<p> This code successfully recognizes hindi characters when user make characters in front of camera. </p>
<h3>Code Requirements </h3>
<p>1. you can install Conda for python which resolves all the dependencies for machine learning.</br>
2. install tensorflow ,  in conda -> $ conda install tensorflow </br>
3. install keras ,  in conda -> $ conda install keras</br>
4. install opencv ,  in conda -> $ conda install opencv</br>
5. handWritingRecognition.py require data set data.csv for training and test</br>
6. application.py require devanagari_model.h5 model for classify the characters.
</p>
<h3> Technique Used </h3>
<p> I have used convolutional neural networks. I am using Tensorflow as the framework and Keras API for providing a high level of abstraction. </p>
<h3> Architecture</h3>
<p> CONV2D --> MAXPOOL --> CONV2D --> MAXPOOL -->FC -->Softmax--> Classification </p>
<h3>Python Implementation</h3>
<p>
1.Dataset- DHCD (Devnagari Character Dataset)<br>
2.Images of size 32 X 32<br>
3.Convolutional Network Support added.<br>
</p>

<h3> Train Acuracy ~ 95% </h3>
  train on 70000 with 8 Epochs</br>
<h3>Test Acuracy ~ 92%</h3>
test on 2001
<h3 > Execution of program </h3>
<p> To train the dataset run file handWritingRecognition.py<br>
To run code type: python3 handWritingRecognition.py</p>
<p> Execution for writing through webcam<br>
type: python3 application.py</p>
