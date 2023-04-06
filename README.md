# IITM-RP-IC-Student-Hackathon-Final-Round-Team-04
sneha2002vijay@gmail.com - Participant private repo for submission to the Detect-IITM-RP-IC Hackathon 2022
*Problem Statement: To detect incorrect lifting of the box by each person in the given video*
Step 1 – Since the Primary concern is detecting the person, kindly make use of resnet which involves a 2 stage classification


Step 2 –  For detecting people’s posture kindly make use of the Implementation of YOLOv7: Pose estimation implementation is based on YOLO-Pose.
          Ref- https://arxiv.org/abs/2204.06806
          
          
Step 3 – For Dataset make use of MS COCO 2017

Step 4 – Then train the model and test the model


Step 5 – Now optimize the solution based on the concept of lower body parts’ angle estimation, where we spot the anomalies in the posture of the person lifting the box.          Here Correct and Incorrect Posture deviate in a particular way, with respect to the angle which we’ve already mentioned.

Bonus:

Blurring Faces of each person in the video: 

Step 1 – Inorder to blur multiple persons’ face in a video, kindly use OpenCV

Step 2 – To detect the face, use ‘haarcascade’ and to blur the face use ‘gaussion blur’

Dropping of Carton Box Detection:

Step 1 - We have used Yolov5 to Detect the Carton Box

Step 2 - With that we detect whether the box is static or not, based on which we use a boolean value to make sure whether the box is dropped or not


