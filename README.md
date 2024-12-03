# Detection of Alzheimer's Disease at Early Stages  

Detecting Alzheimer’s disease at its early stages using Convolutional Neural Network (CNN) models. The project utilizes a large dataset of brain MRI images, categorized into four classes: **MildDemented**, **ModerateDemented**, **NonDemented**, and **VeryMildDemented**.

---

## Dataset Overview  

The dataset is stored on [Google Drive](https://drive.google.com/drive/folders/1T4zhsSvXk5nKJhscvPTYbqwJXo8QJERF?usp=drive_link) due to its large size.  

### **Training Data**  
- **MildDemented**: 717 images  
- **ModerateDemented**: 52 images  
- **NonDemented**: 2560 images  
- **VeryMildDemented**: 1792 images  

### **Testing Data**  
- **MildDemented**: 179 images  
- **ModerateDemented**: 12 images  
- **NonDemented**: 640 images  
- **VeryMildDemented**: 448 images  

---

## Model Performance  

### **1. CNN Model**  
- **Test Loss**: 0.0478  
- **Test Accuracy**: 98.70%  

#### **Classification Report**  
| Class | Precision | Recall | F1-Score | Support |  
|-------|-----------|--------|----------|---------|  
| 0     | 1.00      | 0.99   | 0.99     | 480     |  
| 1     | 1.00      | 1.00   | 1.00     | 480     |  
| 2     | 0.98      | 0.97   | 0.98     | 480     |  
| 3     | 0.97      | 0.98   | 0.98     | 480     |  

### **2. CNN_2 Model**  
#### **Classification Report**  
| Class               | Precision | Recall | F1-Score | Support |  
|---------------------|-----------|--------|----------|---------|  
| MildDemented        | 0.00      | 0.00   | 0.00     | 179     |  
| ModerateDemented    | 0.00      | 0.00   | 0.00     | 12      |  
| NonDemented         | 0.61      | 0.83   | 0.70     | 640     |  
| VeryMildDemented    | 0.43      | 0.40   | 0.41     | 448     |  

- **Overall Accuracy**: 55%  

---

## Features  
1. **Data Preprocessing**: Image resizing, normalization, and augmentation for better model training.  
2. **Model Implementation**: Two distinct CNN architectures were employed for classification.  
3. **Evaluation Metrics**: Precision, Recall, F1-Score, and Accuracy.  
4. **Visualizations**: Graphs showcasing model performance and class-wise predictions.  
