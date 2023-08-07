## DL II Math Final Project Report:    
   
## Creating 3D images/clips from 2D images  
  
### Group Members:
Dusan Birtasevic  
Kavian Mashayekhi  
Narjes Amusoltani  
Tina Khazaee  
  
Welcome to the DL II Math Final Project index page.  
  
This index file has been created to refrence different parts of the project. You can see Table of content below and can have access to different parts of the project throgh the provided links. 
  
The index page of the project with access to the all parts could be found below:  
https://kawians.github.io/DLIIMathProject/ 
  
  
### Notebooks:  
  
1. [Project Report ](https://kawians.github.io/DLIIMathProject/DLIIReport.html)  
  
2. [YOLO V8 ](https://kawians.github.io/DLIIMathProject/yolov8_face_detection.html)  
  
3. [Image Super-Resolution using an Efficient Sub-Pixel CNN ](https://kawians.github.io/DLIIMathProject/Image%20Enhancement.html)  
  
4. [Fine Tuning of Image Super-Resolution using an Efficient Sub-Pixel CNN ](https://kawians.github.io/DLIIMathProject/Fine_Tuning.html)  
  
5. [First Order Motion ](https://github.com/Kawians/DLIIMathProject/blob/main/Notebooks/First_Order_Motion.ipynb)  
  
6. [ESRGAN Image Enhancement ](https://kawians.github.io/DLIIMathProject/ESRGAN_Image_Enhancement.html)  
  
7. [ESRGAN Video Enhancement ](https://kawians.github.io/DLIIMathProject/ESRGAN_Video_Enhancement.html)  
  
  
### Repositories:  
  
1- Notebooks, Report, HTML generated files Repository:  
https://github.com/Kawians/DLIIMathProject/  
  
2- Streamlit Repository:  
https://github.com/dusanBirta/test_repo/tree/main
  
3- Streamlit App link:  
https://testrepo-y12d7zyos0a.streamlit.app/
  

### Project Abstract  
  
  
This computer vision project introduces a method for generating facial 3D images/clips from 2D images, with a focus on enhancing facial details and creating captivating 3D animations.  
The pipeline combines YOLOv8 for face detection, an Efficient Sub-Pixel Convolutional Neural Network (CNN) for Image Super-Resolution, Real ESRGAN for realistic enhancement, and the First Order Motion Model for animation synthesis.  
  
Initially, YOLOv8 accurately localizes and extracts facial regions from input 2D images. These faces are then cropped and passed to the Efficient Sub-Pixel CNN, a powerful network that reconstructs high-resolution facial images, significantly improving facial quality and detail.
  
Input Image:  
  
<img src="https://user-images.githubusercontent.com/31896340/258622473-274280a6-4f6a-4d37-aa9b-afdfa2a8e144.png" alt="Input Image" style="width:300px;height:200px;">

Prediction (yolov8_face_detection Notebook):  
  
<img src="https://user-images.githubusercontent.com/31896340/258622484-bd7d28d0-4e25-43c5-ab47-d21f65fab4b7.jpg" alt="Input Image" style="width:300px;height:200px;">
  
  
Bounding Box Crop (yolov8_face_detection Notebook):  
  
<img src="https://user-images.githubusercontent.com/31896340/258622506-9819d3db-04f0-4bc0-bdaf-e71d65b9d413.jpg" alt="Input Image">  
  
To further enhance the upscaled images, Real ESRGAN, a specialized Generative Adversarial Network (GAN) for super-resolution tasks, is utilized to generate visually realistic and finely-detailed facial representations.  

Lastly, the First Order Motion Model breathes life into the enhanced facial images, allowing for the creation of dynamic 3D animations. The model transfers facial movements from source videos to the improved 3D facial representations, resulting in realistic and captivating visualizations.  
  
Enhanced Image (ESRGAN_Image_Enhancement Notebook):  
  
<img src="https://user-images.githubusercontent.com/31896340/258648975-53a4a752-89c9-4df3-9fb2-cfd076ad5c2e.jpg" alt="Input Image" style="width:200px;height:250px;">
  
  
Animate 2d Picture (First Order Motion Notebook):  
  
<video controls>
  <source src="https://github.com/Kawians/DLIIMathProject/assets/31896340/e8447a7e-d7e9-4607-ba7e-c0b202a59956" type="video/mp4">
  Your browser does not support the video tag.
</video>  
  
Enhance Video (ESRGAN_Video_Enhancement Notebook):  
  
<video controls>
  <source src="https://github.com/Kawians/DLIIMathProject/assets/31896340/f674f43f-966c-4a65-b8c5-6f98d32e24e8" type="video/mp4" >
  Your browser does not support the video tag.
</video>  
  
Our primary motivation was to enhance facial details in 2D images and produce compelling 3D animations. The potential applications of this technology range from aiding suspect identification for law enforcement to capturing evidence of thieves caught on security cameras.  
  
Through comprehensive experimentation and evaluation, our approach demonstrates substantial improvements in facial details, animation realism, and overall visual appeal. This project contributes to the field of computer vision by opening up possibilities for advancements in facial enhancement and animation synthesis, with promising applications in security, entertainment, and various other domains.  
  






# Results of Notebooks

### Input Image:

![devito](https://github.com/Kawians/DLIIMathProject/assets/31896340/274280a6-4f6a-4d37-aa9b-afdfa2a8e144)

### Prediction (yolov8_face_detection Notebook):

![results](https://github.com/Kawians/DLIIMathProject/assets/31896340/bd7d28d0-4e25-43c5-ab47-d21f65fab4b7)

### Bounding Box Crop (yolov8_face_detection Notebook):

![face_0](https://github.com/Kawians/DLIIMathProject/assets/31896340/9819d3db-04f0-4bc0-bdaf-e71d65b9d413)

### Enhanced Image (ESRGAN_Image_Enhancement Notebook):

![face_0_out](https://github.com/Kawians/DLIIMathProject/assets/31896340/53a4a752-89c9-4df3-9fb2-cfd076ad5c2e)

### Animate 2d Picture (First Order Motion Notebook):

https://github.com/Kawians/DLIIMathProject/assets/31896340/e8447a7e-d7e9-4607-ba7e-c0b202a59956

### Enhance Video (ESRGAN_Video_Enhancement Notebook):

https://github.com/Kawians/DLIIMathProject/assets/31896340/f674f43f-966c-4a65-b8c5-6f98d32e24e8









