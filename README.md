Driver Drowsiness Detection System
Overview
  1.The Driver Drowsiness Detection System is a deep learning-based application designed to monitor a driver’s facial expressions and 
  detect signs of fatigue or drowsiness in real time. The system helps improve road safety by alerting the driver whenever signs of sleepiness are detected.
  2.This project uses Computer Vision and Deep Learning techniques to classify driver states such as:
        Open Eyes
        Closed Eyes
        Yawning
        No Yawning
Based on these predictions, the system determines the driver’s fatigue level and generates alerts to prevent accidents caused by drowsy driving.

Technologies Used:  
       Python
       TensorFlow / Keras
       PyTorch
       NumPy
       Pandas
       Matplotlib
       Scikit-learn

Dataset:
The dataset consists of driver facial images categorized into four classes:
       Closed
       Open
       Yawn
       No_Yawn

Project Workflow:
1. Data Collection
      Collect driver face images/videos
      Organize into class folders
2. Data Preprocessing
      Resize images
      Normalize pixel values
      Perform image augmentation
3. Model Building
Two models were implemented:
     CNN Model for image classification
     MobileNetV2 Transfer Learning model for improved accuracy.

4. Training:
     Optimizer: Adam
     Loss Function: Crossentropy

5.Evaluation Metrics:
     Accuracy
     Precision
     Recall
     confusion matrix

 6. Prediction
The trained model predicts driver conditions in real time.

7. Fatigue Classification Logic
Predicted Class	Fatigue Level
     Open + No_Yawn	----> Alert
     Open + Yawn	----> Mild Fatigue
     Closed ---->	Severe Fatigue

Conclusion:
This project demonstrates how Deep Learning and Computer Vision can be used to build an intelligent driver monitoring system.
The Driver Drowsiness Detection System helps reduce road accidents by detecting fatigue signs early and providing timely alerts to the driver.
















       

    
