# 📰 Fake News Detector - AI Text Classifier

This project is a machine learning model that can predict whether a news article is **real** or **fake** based on its content.  
It uses a neural network built with TensorFlow and trained on the popular `Fake.csv` and `True.csv` datasets.

## 🔍 About the Project

- Combines fake and true news datasets
- Cleans and prepares the data
- Uses text tokenization and padding
- Trains a binary classification model
- Evaluates accuracy and loss across epochs
- Allows real-time prediction with custom news headlines

## 📊 Model Performance

Achieved **over 98% training accuracy** and solid validation performance.

<img width="1071" height="588" alt="image" src="https://github.com/user-attachments/assets/587f22e2-f0cc-4ab0-bc3e-07526a9c4134" />



## 🧪 Try It Out

```python
predict_news("Breaking: Scientists discover new planet in our solar system")
# Output: Prediction: Fake (confidence: 0.00)
