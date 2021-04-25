# Car_Brand_Classification
This is a Image Classification Technique and classified with Deep Learning which classifies car which belongs to any of the 10 classes
Those classes are <b>Audi , Lamborghini , Mercedes , KIA , Suzuki , Tata , Ford , Lexus , Honda , Mahindra</b>

The front end is developed with the help of Gradio which provides an Interface which is readily available for Data Scientists which avoids using HTML,CSS,JavaScript and this is mainly useful for POC purpose and this classification is done using Creating the Architecture from scratch and then shifted to the transfer learning techniques such as InceptionV3 and VGG16 for getting better prediction

<h1>The below page is the Front End for the Application which is developed using Gradio</h1>

<img src = "fend.png">

<b>The next image is the continution image here we have the various classes of cars as the sample images</b>

<img src = "fe1.png">


Now we will test on one of the image and see the prediction from both the Transfer Learning Architectures
The top one is InceptionV3 and the bottom one is the VGG16 and here we ouput the top 3 classes classified for the cars
<br>
<h1>Testing and getting the results</h1>
<img src="lamb1.png">


Here we ca see that both the architectures gave us the right predictions for the car but there are some errors and these two techniques gives us good performance and also helps us to identify the classes of the cars accurately

<b>Front End Tool</b> <br>
Gradio <br>

<b>IDE</b><br>
Jupyter Notebook

<br>
<b>Deep Learning Framewrok</b><br>
 Tensorflow
 

<img src= "gradio.png">  &nbsp;&nbsp;&nbsp;&nbsp;    <img src="tf.png">    &nbsp;&nbsp;&nbsp;&nbsp;   <img src="jupyter.png" height=150 width= 150>

<h1>Work Flow for the Project</h1>

<h1>Data Collection</h1><br>
All these images are being scraped from the web using the <b>Simple Image download module from python</b> and these images are of two extensions <b>jpeg</b> and <b>png</b> and these images are provided by various websites
<br><br>

<h1>Data Preprocessing</h1><br> 
The data is split into training and test and the training data is applied with various tranformations such as horizontal flip , zoom in , zoom out , shear range and scaling etc
<br>
The test data is scaling as we cant apply any transformations to the test data

<br><br>

<h1>Model Creation</h1> <br>
Total Three Architectures are created one is the base model and which is created from scratch and other two are the transfer learning techniques such as InceptionV3 and VGG16 which improved the performance of the model<br>
<br>
<b>The accuarcies of the models used for classification :</b> <br><br>
<b>Architectures</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      <b>Accuracies</b><br>
<b>1.Base Model</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          <b>91%</b>  <br>
<b>2.InceptionV3</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      <b>98%</b> <br>
<b>3.VGG16</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    <b>98%</b>
Ravi
<br><br>
<h1>If anyone like my project and want to know more about it. I am giving my LinkedIn Profile and if you want we can connect there</h1>
<br><br>
<a href = https://www.linkedin.com/in/ravi-shankar-94b587174>My linkedIn profile</a>
