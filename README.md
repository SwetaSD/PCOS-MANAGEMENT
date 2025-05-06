# 🧬 PCOS Detection Using Ultrasound Images

## 📖 About the Project
This project aims to detect Polycystic Ovary Syndrome (PCOS) using ultrasound images of ovaries with the help of Deep Learning. PCOS is a hormonal disorder common among women of reproductive age and is often characterized by irregular menstrual periods, excess androgen levels, and polycystic ovaries. Early detection can assist in better medical guidance and treatment planning.

## 🛠️ Tech Stack Used
- **Languages**: Python  
- **Libraries**: TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib  
- **Model**: Pre-trained **VGG16** CNN  
- **Platform**: Google Colab
- **Dataset**:Ultrasound images for PCOS Detection from Kaggle

## 🧪 Model Summary
We used VGG16, a powerful CNN architecture pre-trained on ImageNet, and fine-tuned it for binary classification (PCOS vs Non-PCOS). VGG16's convolutional layers were used to extract features from ultrasound images, and a custom classifier was added on top.

## 📊 Results
- Achieved satisfactory accuracy in distinguishing between PCOS and Non-PCOS ultrasound images.
- Visualizations include accuracy/loss graphs and sample predictions.

## 📁 Dataset
- **Source**: [Kaggle - Pcos Detection Using Ultrasound Images](https://www.kaggle.com/datasets/anaghachoudhari/pcos-detection-using-ultrasound-images)
- Consists of labeled ultrasound images for PCOS and NON-PCOS cases.
