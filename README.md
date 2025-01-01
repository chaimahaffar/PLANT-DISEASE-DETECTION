<h1>Plant Disease Detection System</h1>

<h2>Description</h2>
This project involves the development of a system to automatically segment plant diseases using leaf images. The system is designed to identify and segment affected areas on the leaves, which helps in the early detection and precise treatment of plant diseases. By accurately detecting and highlighting the diseased portions, the system improves the overall management and care of plants. 
<br />

<h2>Technologies Used</h2>
- <b>Detectron2</b> 
- <b>Image Processing</b>
- <b>Roboflow</b> (for annotating images in COCO format)

<h2>Environments Used</h2>
- <b>Python</b> 
- <b>OpenCV</b> (for image processing)
- <b>Google Colab</b> (for model training and testing)

<h2>Data Collection and Annotation using Roboflow</h2>

<p>
This project begins with collecting plant leaf images and annotating them using **Roboflow**. Roboflow provides an easy-to-use platform for image annotation, where we mark the affected areas of the plant leaves corresponding to different diseases. Below are the steps of the annotation process:
</p>

<p align="center">
  Annotating the images with **Roboflow**: <br/>
  <img src="https://i.imgur.com/yAVgNnE.png" height="80%" width="80%" alt="Data Annotation Step 1"/><br />
  <br />


<h2>Data Processing and Labeled Format Verification</h2>

<p>
After the annotation, the data needs to be processed. The images are organized into appropriate directories, and the labels are verified to be in the correct format (COCO or Pascal VOC). This step ensures that the data is ready for training and can be fed into machine learning models like **Detectron2**. At this stage, no images are included, but it is crucial to ensure that all the data is properly formatted for the training process.
</p>

<h2>Running the Code and Evaluation</h2>

<p>
Once the dataset is ready, the code is run to train the model using **Detectron2**. The model is trained on the annotated images, and its performance is evaluated based on metrics like accuracy, precision, and recall.
</p>

<p align="center">
  Final result: <br/>
  <img src="https://i.imgur.com/9uM4ASz.png" height="80%" width="80%" alt="Final result"/><br />
</p> 

