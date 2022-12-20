# Data_Analytics_Final_Project
**Detection of Skin Cancer Based on Skin Lesion Images Using Deep Learning**

### Description  
Skin cancer is one of the most common types of cancer worldwide. Well, some studies show that if you get more than 5 sunburns your chances of getting a malignant cancer doubles. One of the proven method to detect skin cancer is using a subpart of artificial intelligence, Deep Learning. In this research, the deep learning method convolution neural network (CNN) was used to detect the two primary types of tumors, malignant and benign, using the ISIC2019 dataset. Further, another prediction was run to detect the "type" of the skin cancer which makes it both binary and a multi-class classification problem.



<img width="779" alt="image" src="https://user-images.githubusercontent.com/114943213/208715943-66cce71f-8d0e-4c0b-a544-9984143badb7.png">
 
 ### Files
 ##### Dataset 
[ISIC Challenge 2019](https://isic-challenge-data.s3.amazonaws.com/2019/ISIC_2019_Training_Metadata.csv) : data files  
[Images folder](https://isic-challenge-data.s3.amazonaws.com/2019/ISIC_2019_Training_Input.zip) : 25,331 metadata

1. data_prep
Model
3. model 1
4. model 2 : binary classification
5. model 3 : multi-class classification
6. visualisation


### Conclusion
<img width="518" alt="Screenshot 2022-12-20 at 5 58 10 PM" src="https://user-images.githubusercontent.com/114943213/208723200-06c752a1-9813-473a-8603-dceb2d3fd8d6.png"> 

1. By analyzing images of lesions on the skin, we developed a technique for quickly
and accurately diagnosing both benign and malignant forms of cancer
2. Malignant or Benign : The **binary** model predicted **77% accuracy** and **68.9% recall** value in detecting cancer. A good recall value is crucial because the recall measures the model's ability to detect **Positive samples**.
3. Type of cancer : The second model achieved an accuracy of **70.3%** and a recall value of **64.3%** in predicting the **type**.
4. Training the model on a **higher image resolution** (256x256x3) on google cloud platforms such as **Vertex AI** and **Google Collab** would yield a better accuracy and thereby better predicted test results.
5. The model can further be improved by **hyper parameter tuning**. 
