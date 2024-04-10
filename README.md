<b>"This project involves implementing object detection using YOLOv5." </b> </br>
if you want to learn yolov5 algorithm you can visit - https://github.com/ultralytics/yolov5 </br></br>

YOLOv5 models must be trained on labeled data in order to learn classes of objects in that data. There are two options for creating your dataset before you start training:</br>
Collect Images </br>
Create Labels </br>
Prepare Dataset for YOLOv5 </br>


. so basically to implement this project you need to download the dataset folder which contains two thing </br>
  1. Images
  2. Annotations
</br>

this is the format for the annotation file</br>
![image](https://github.com/chandranavinn/object_detection_using_yolov5/assets/73417896/bdbd5caf-9683-46af-a14b-0b50051e0a48)

</br>
. images have 3 files test train val </br>
. and labels have 2 files train and val </br>
. label files contain Txt files and image files contain JPG files </br>
. this is the required format for yolov5 </br>
Organize Directories in this format 

![image](https://github.com/chandranavinn/object_detection_using_yolov5/assets/73417896/df1b5a52-73e5-48b4-9143-666ca8c72301)

. and the dataset files uploaded here are also arranged in the same required format for yolov5 </br>


</br>...................................yolov5..........................................</br>
Now let's go to the implementation of the project to implement you just need to download the dataset </br>
and after downloading you need to put some commands in your vs-code terminal to use yolov5.</br>

  1. git clone https://github.com/ultralytics/yolov5  # clone
  2. cd yolov5
  3. pip install -r requirements.txt  # install
</br>
so this will import yolov5 and also  install the requirements needed for yolov5</br>

after all the requirements are installed you need to check whether annotations are correct or not</br>

to verify the same you need the CV2 algorithm</br>

you can go through demo.ipynb file which contains the code to verify the annotations </br>

you only need to change the path of annotations and image file </br>

this will show some output like this </br>
![image](https://github.com/chandranavinn/object_detection_using_yolov5/assets/73417896/9fcd5317-497a-4424-9eda-d178de307d3d)

if you are getting the image output means your file contains correct data now you can move ahead </br>

now to implement yolov5 read this documentation for a better understanding https://docs.ultralytics.com/yolov5/tutorials/train_custom_data/#22-create-labels </br>
