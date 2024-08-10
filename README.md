# Plastic-Paper-Garbage_bag_segmentation

In this project we will use image segmentation to classify and segment garbage, paper and plastic bags.
This will help us to segregate waste by classifying garbage bags which can be recycled, plastic bags which are not easily dispossable and paper bags which are easily dispossable.

![test_image](https://github.com/user-attachments/assets/49fd85e1-28c5-433e-8fd1-fd80bbbde984)

**Image Segmentation**

Image segmentation is computer vision task which is bit more advanced than object detection. In segmentation we assign label to objects at pixel level, which help us to detect exact location and shape of an object. Image segmentation is useful in many cases where we need not onlt to detect specific object but also its shape. There are two types of segmentation Semantic segmentation and Instance segmentation. In semantic segmentation  we apply label to each object pixel in an image and in instance segmentation we apply label to each pixel and furthermore it distguish between indivisual class instance.


**Instance Segmentation**

In this project I have used instance segmentation to segment paper, plastic and garbage bags. 
Instance segmentation is a part of semantic segmentation which is used to segmnt object belonging to same class, instance segmentation goes one step further by segmenting object of same class as well.

**YOLOv8 segmentation**

Yolov8 is latest version of SOTA (Steate-Of-The-Art) YOLO model introduced by Ultralytics which is suitable for range of computer vision tasks, including object detection, segmentation, pose estimation, classification and tracking. YOLOv8 is faster and more accurate than its previous versions. 
YOLOV8 segmentation model adds additional segmentation head into traditional YOLOV8 detection model, which provides precise pixel level segmentation and its integrated with YOLOv8 architecture provides seamless combination of object deteaction and segentation. YOLOV8 achieves high level of accuracy in objet detection, which provides a basic foundation for segmentation model by accyrately localizing correctly identifying object from image.

YOLOv8 segmentation doesn't perform instance segmentation directly, it actually performs semantic segmentation on an image by assigning label to each pixel of an object.
It then does post-processing techniques such as clustering and boundary refinement to differentiate between individual instance of same class.

