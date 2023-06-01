# staff_detection

 + Object detection using Yolo, pretained pytorch model from Yolo
 + Retrive frames with person detected.
 + Save retrieved frames to output folder.
 + Select images for train test (20 selected in total), 1 image selected for inference, selected images are removed from output folder.
 + Selected images stored in train_yes, train_no and test folder
 + SVM classification
 + Trained model saved as pkl files
 + Remaining frames in output folder are predicted
 + Predicted result copied and separated into two folders, test_staff_result_frame (for frame with staff), test_non_staff_result_frame (for frame without staff)
 + For details of the implementation please check Staff Detection.ipynb

# Design

![alt text](Isolated.png "Flow of Detection")