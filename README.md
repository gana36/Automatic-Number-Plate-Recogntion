# Automatic-Number-Plate-Recogntion

# Introduction

Automatic Number plate recognition is a computer vision practice that allows devices to read license plates of the vehicles quickly and automatically

Automatic Number plate recognition has a wide range of use cases in the real time world applications.

# Objective

To Detect License plates of Vehicles entering and leaving Campus.

To Create a real time dataset of Number Plates captured at different Environmental Conditions .

To Maintain log of  Vehicle Number Plates entering or leaving the campus including time in and time out

# Dataset 

For Training the model: 

     This Dataset contains 433 images with annotations of the license plates of the cars in the image

     Link : https://www.kaggle.com/andrewmvd/car-plate-detection

For Testing the model:

         This Dataset contains 200 images of cars with license plates and annotations.

        Link : https://drive.google.com/file/d/1QAFdt5Mq8X6fZud7kdsjaJbJfSXrsFse/view?usp=sharing 
        
# Workflow 

![image](https://user-images.githubusercontent.com/71372490/162795768-cc9d0545-d968-4ffb-a03d-3a9faf48e7c6.png)

        
# Challenges Faced  and Solutions applied

Saving the Video/photos from the CCTV to local PC for future evaluation and use cases is done by adding the CCTV running port as a trusted site.

Lag between the Python window and the feed from the CCTV which causes to break the model is rectified by skipping the frames

Text Extraction from the Licence plate is optimised in such a way that most of time it neglects the un-wanted text in the Licence plate.

Skipping frames in saved video works fine, but just skipping frames in the real time feed not solved all problems, this is solved by reading the feed from CCTV 2 times.

        
# Real Time Results 

![re_det_1](https://github.com/user-attachments/assets/7bc47f3e-92ac-4908-b76a-d0dfe2195aab)
![det_4](https://github.com/user-attachments/assets/43827233-a9be-44eb-aecb-6cab1e0a5de1)
![det_3](https://github.com/user-attachments/assets/d678bfe9-63c9-47bf-94b4-0bbc2542fbf9)
