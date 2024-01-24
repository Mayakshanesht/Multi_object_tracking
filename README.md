# object_tracking_new- refer version 2
Here we have two tasks to perform:

A. detection using YOLO v3 from open CV library

take out detected object and bounding boxes for the object detected

B. Data Association using Hungarian method:
so that we could create track out of object detected in the image
Since this approach further need to be appended with kalman filter to get beeter accuracy at higher vehicle speed
