# Automatic-Number-Plate-Recogntion

# Introduction

Automatic Number plate recognition is a computer vision practice that allows devices to read license plates of the vehicles quickly and automatically

Automatic Number plate recognition has a wide range of use cases in the real-time applications.

# Objective

To Detect License plates of Vehicles entering and leaving Campus.

To create a real-time dataset of number plates captured under different conditions.

To Maintain a log of  Vehicle Number Plates entering or leaving the campus including time in and time out

# Dataset 

For Training the model: 

     This Dataset contains 433 images with annotations of the license plates of the cars in the image

     Link : https://www.kaggle.com/andrewmvd/car-plate-detection

For Testing the model:

         This Dataset contains 200 images of cars with license plates and annotations.

        Link : https://drive.google.com/file/d/1QAFdt5Mq8X6fZud7kdsjaJbJfSXrsFse/view?usp=sharing 
        
# Workflow 

![anpr](https://github.com/user-attachments/assets/f9e457ac-0294-43d2-aecc-96ef022d127e)


        
# Challenges Faced  and Solutions applied

The lag between the Python window and the feed from the CCTV was synchronised by skipping the frames this helped to fix the breakdown of mthe odule

Text Extraction from the Licence plate is optimised so that most of the time it neglects un-wanted text in the Licence plate.

The module could detect plates from a saved file but failed to perform in real-time. This was fixed by feeding the frames to the model 2 times consecutively. 


        
# Real Time Results 

![re_det_1](https://github.com/user-attachments/assets/7bc47f3e-92ac-4908-b76a-d0dfe2195aab)
![det_4](https://github.com/user-attachments/assets/43827233-a9be-44eb-aecb-6cab1e0a5de1)
![det_3](https://github.com/user-attachments/assets/d678bfe9-63c9-47bf-94b4-0bbc2542fbf9)
