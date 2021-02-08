# vehicle_speed_estimation

In this project I am using yolov3 for object detection (mainly detecting cars bike truck bus and other vehicles)

later i am using computer vision code for estimating speed
In this I am traking the object first and getting the centroids of thet detected object

later i am going frame by frame and analysing the pixel diffrence created by vehicle
later we use this diffrence to calculate pixel per frames and with that we can easily come up with speed 


Speed Estimation

speed = ( d_pixel x fs x 3.6)/ppm

Where: d_pixel: distance between two position of detected car.

in this case to getting pixel per frame we are simply couting the pixels paassed by vehicle in 1min 

and later we can get the full speed to vehicle to simplfy this and getting the distence betteen two positions I am using our famous distance formula between two cordinates

dist_pixel = math.sqrt((x1-x2)**2 - (y1-y2)**2)

and getting the distance between two points or better call it number of pixels between two points 
