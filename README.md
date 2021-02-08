# vehicle_speed_estimation

In this project I am using yolov3 for object detection (mainly detecting cars bike truck bus and other vehicles)

later i am using computer vision code for estimating speed
In this I am traking the object first and getting the centroids of thet detected object

later i am going frame by frame and analysing the pixel diffrence created by vehicle
later we use this diffrence to calculate pixel per frames and with that we can easily come up with speed 
