# Object-Detection-and-Tracking
This repository contains a computer vision project for tracking the movement of colored balls across various quadrants in a video. The program records events when each ball enters and exits numbered quadrants, and outputs the results in both video and text formats.

contains two programms one with pre trained model and one custom made

# YOLOv3 Version
This version utilizes a pre-trained YOLOv3 model for object detection. Here are some key points:

Advantages:

-Detects the object accurately.

-Utilizes a robust pre-trained model trained on a large dataset.

-Generally higher accuracy in detecting objects like balls.

Limitations encountered in the project:

-fails to identify the entry/ exit event.

-unable to detect the color accurately.

-Dependency on the availability of a suitable pre-trained model.

-May require significant computational resources for inference.

# Custom Object Detection Version
This version implements custom object detection without relying on a pre-trained model :

Advantages:

-Provides flexibility to fine-tune object detection specifically for colored balls.

-Lower computational requirements compared to the pre-trained model approach.

Limitations:

-fails to detect the quadrant region and entry\exit event.

-Initial training phase required to detect balls accurately.

-May have lower accuracy compared to the pre-trained YOLOv3 model, especially without extensive training data.
