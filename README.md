# Car_Brand-Classification
This is a Image Classification Technique and classified with Deep Learning which classifies car which belongs to any of the 10 classes
Those classes are <b>Audi , Lamborghini , Mercedes , KIA , Suzuki , Tata , Ford , Lexus , Honda , Mahindra</b>

All these images are being scraped from the web using the simple image download module from python

The front end is developed with the help of Gradio which provides an Interface which is readily available for Data Scientists which avoids using HTML,CSS,JavaScript and this is mainly useful for POC purpose and this classification is done using Creating the Architecture from scratch and then shifted to the transfer learning techniques such as InceptionV3 and VGG16 for getting better prediction

The below page is the Front End for the Application which is developed using Gradio

<img src = "fend.png">

The next image is the continution image here we have the various classes of cars as the sample images

<img src = "fe1.png">


Now we will test on one of the image and see the prediction from both the Transfer Learning Architectures
The top one is InceptionV3 and the bottom one is the VGG16 and here we ouput the top 3 classes classified for the cars

<img src="lamb1.png">


Here we ca see that both the architectures gave us the right predictions for the car but there are some errors and these two techniques gives us good performance and also helps us to identify the classes of the cars accurately

<b>Front End Tool</b>

<img src= "gradio.png">

<b>The accuarcies of the models used for classification</b>: <br>
<b>Architectures</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       <b>Accuracies</b><br>
<b>Base Model</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ----      <b>91%</b>  <br>
<b>InceptionV3</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   ----    <b>98%</b> <br>
<b>VGG16</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         ----         <b>99%</b>


<b>Deep Learning Framework </b>

<img src="tf.png">
