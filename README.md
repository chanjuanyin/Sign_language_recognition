# Sign_language_recognition

Module EE8101 Exploring DEEP in Innovation: Deep learning in image recognition (Jan – May 2021)

---

### **Overview**

This is a project done for our NTU module EE8101 Exploring DEEP in Innovation. 

Our group developed a sign-language interpretation model to recognise hand gestures and convert them into English words. 

---

### **Model specification**

Sign language interpretation model to covert hand gestures to words. Model based on GRU and LSTM architecture to perform video classification. Implementation based on PyTorch. Hand landmark features were extracted with Google MediaPipe. Data pre-processing and augmentation based on Numpy.

File contains steps of hyperparameter grid search: sequence length, hidden layer size, batch size, learning rate. Also conducted comparisons with different models: GRU vs MLP vs LSTM, bi-directional model training etc.

Achieved ~53% accuracy on validation dataset, about 50% accuracy on actual testing.

---
