# Exploring Image Classification & Facial Recognition Techniques

## 🔗 Project Links

-  [Project Page](https://kruttichhwas.github.io/face-recognition-website/)  
 


## Introduction

In this project, we explore various techniques for **image classification** and **facial recognition**, focusing on a comparative analysis of:

- **Local Binary Pattern (LBP)**
- **Histogram of Oriented Gradients (HoG)**
- **Convolutional Neural Networks (CNN)**

Our goal is to evaluate the effectiveness of each method in terms of feature extraction and classification accuracy.

---

## Dataset

We used the **LFW (Labeled Faces in the Wild)** dataset — a widely recognized benchmark for facial recognition tasks.

- **Number of images**: 1288  
- **Image size**: 50 x 37  
- **Number of unique classes**: 7  
- **Target class names**:  
  `['Ariel Sharon', 'Colin Powell', 'Donald Rumsfeld', 'George W Bush', 'Gerhard Schroeder', 'Hugo Chavez', 'Tony Blair']`

---

## Feature Extraction Techniques

###  1. Local Binary Pattern (LBP)
- Implemented both from scratch and using the `skimage` library
- Visualized LBP-transformed images
- Extracted features used for classification

###  2. Histogram of Oriented Gradients (HoG)
- Resized images to 64 x 128 for consistency
- Detected vertical and horizontal gradients
- Computed magnitudes and orientations
- Extracted HoG features and visualized them

###  3. Convolutional Neural Networks (CNN)
- Built a lightweight CNN model using **Keras**
- Trained the network on the LFW dataset
- Visualized activations from CNN layers
- Extracted CNN features for classification

---

## Classification Models

We evaluated three classification models on features extracted by LBP, HoG, and CNN:

- **Support Vector Machine (SVM)**
  - Evaluated using accuracy and classification reports
- **K-Nearest Neighbors (KNN)**
  - Assessed performance on all feature sets
- **Decision Trees**
  - Compared with SVM and KNN using confusion matrices

---

## Results and Discussion

- Included classification reports and confusion matrices
- Compared the precision, recall, and F1-scores for all techniques
- Discussed strengths and weaknesses of:
  - LBP (fast, less expressive)
  - HoG (robust to illumination)
  - CNN (best performance, requires more data and training)

---

## Conclusion

- CNN outperformed other techniques in overall accuracy
- LBP and HoG serve as efficient traditional feature extractors
- Future work may explore transfer learning or deeper CNN architectures for improved results

---

## Try it Yourself!

- [Open in Google Colab](#)


---

>  *This project serves as a practical demonstration of classical vs. deep learning methods for facial recognition. Perfect for anyone interested in computer vision!*
