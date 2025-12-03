<h1 align="center">🌱 Plant Disease Detection System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Detectron2-Model-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Image%20Processing-OpenCV-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Roboflow-Annotation-red?style=for-the-badge" />
</p>

---

<h2>Description</h2>

<p>
This project involves the development of a system to automatically segment plant diseases using leaf images. The system is designed to identify and segment affected areas on the leaves, enabling early detection and precise treatment of plant diseases. By accurately detecting and highlighting diseased portions, the system improves overall plant management and care.
</p>

---

<h2>Technologies Used</h2>
<ul>
  <li><b>Detectron2</b> – Object detection and instance segmentation</li>
  <li><b>Image Processing</b> – Preprocessing and enhancement of leaf images</li>
  <li><b>Roboflow</b> – Annotating images in COCO format</li>
</ul>

---

<h2>Data Collection and Annotation using Roboflow</h2>

<p>
The project begins with collecting plant leaf images and annotating them using <b>Roboflow</b>. Roboflow provides an easy-to-use platform for image annotation, where affected areas of plant leaves corresponding to different diseases are marked. Below are examples of the annotation process:
</p>

<p align="center">
  <img src="https://i.imgur.com/yAVgNnE.png" height="50%" width="50%" alt="Data Annotation Step 1"/><br/>
  <em>Annotating plant leaf images using Roboflow</em>
</p>

---

<h2>Data Processing and Labeled Format Verification</h2>

<p>
After annotation, the data is organized into directories, and labels are verified to be in the correct format (COCO or Pascal VOC). This ensures that the dataset is ready for training and compatible with machine learning models like <b>Detectron2</b>. Proper formatting at this stage is critical for successful model training.
</p>

---

<h2>Running the Code and Evaluation</h2>

<p>
Once the dataset is ready, the model is trained using <b>Detectron2</b>. Its performance is evaluated using metrics such as accuracy, precision, and recall to ensure reliable disease detection and segmentation.
</p>

<p align="center">
  <img src="https://i.imgur.com/9uM4ASz.png" height="50%" width="50%" alt="Final Result"/><br/>
  <em>Final segmentation results showing diseased areas on leaves</em>
</p>

---

<h2>Features</h2>
<ul>
  <li>Automatic segmentation of plant diseases</li>
  <li>Accurate detection of affected leaf areas</li>
  <li>Supports early intervention and plant care</li>
  <li>Data annotation and verification workflow with Roboflow</li>
  <li>Evaluation of model performance using standard metrics</li>
</ul>

---
