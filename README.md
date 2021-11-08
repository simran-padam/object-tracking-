# object-tracking-
The code tracks and counts the vehicles on the highway through a stable toll camera. 


The process of the code is as follows:

- The code attempts to remove the background by masking the frame and identifies the object by finding contours. 
- After defining the contours, we extract the region of interest to allow the code to count and track the vehicles within the area. 
- Tracking and counting of the vehicles is based on the euclidean distance approach, if the frame is similar and within the threshold selected, the vehicle is treated as the same. 

 #Shortcomings 
 - The current implementation works well with stable camera only.
 - In the highway video, there is some error of detection with slight movement of camera.
