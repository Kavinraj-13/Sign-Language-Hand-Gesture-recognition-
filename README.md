# Sign Language Recognition (SLR)  

##  Project Overview  
This project focuses on **Sign Language Recognition (SLR)** using deep learning techniques. We built a system that recognizes hand gestures corresponding to 26 alphabet characters. The goal is to develop an accurate and efficient model for sign language recognition.  

##  Dataset Collection  
- We collected our own dataset consisting of **26 alphabet characters**.  
- Each letter has **100 images**, resulting in a well-balanced dataset.  
- The images capture different hand postures for each character to ensure robustness.  

###  Sample Dataset Images  
Here are some example images from our dataset:  

![Untitled design (3)](https://github.com/user-attachments/assets/0443e301-772a-4192-b28e-683909a8d087)


##  Data Processing  
- We **segmented** the key strokes of the hand gestures.  
- The extracted features were stored as **Pickle (.pkl) files** for efficient data handling and training.  

##  Model Architecture  
- A **Convolutional Neural Network (CNN)** was used to train the model.  
- The model was fine-tuned to achieve high accuracy.  

##  Model Performance  
- The trained CNN model achieved **99% accuracy** in recognizing sign language gestures.  

###  Prediction Results  
The model successfully recognizes various hand gestures. Below is a sample output of the model predicting a sign:  
<img width="949" alt="Screenshot 2025-01-30 at 5 40 58 PM" src="https://github.com/user-attachments/assets/7986d3df-8351-4296-bbba-2cd2e42a9b7e" />

##  Future Enhancements  
In future work, we aim to:  
1. **Integrate Video Sequence Analysis** – Instead of recognizing individual characters, we will process **video sequences** to identify gestures dynamically.  
2. **Feature Extraction from Video** – We will extract **temporal features** from video frames to improve recognition.  
3. **Sentence Formation** – The system will detect multiple gestures and **form meaningful sentences** to enhance communication.  

##  Technologies Used  
- **Python**  
- **TensorFlow / Keras**  
- **OpenCV**  
- **Pickle for data storage**  
- **Deep Learning (CNN)**
- **Flask Framework**


###  Contact  
For more information or contributions, feel free to reach out!  

####  **Email**: [@Nandhini](mailto:nandhinigopal50@gmail.com)
####  **Email**: [@Kavinraj](mailto:kavinr707@gmail.com)

---

This updated **README** includes **sample images of the dataset** and a **visual representation of the model’s predictions**. 🎯 Let me know if you need any more refinements! 🚀  
