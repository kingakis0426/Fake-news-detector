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

<img src="path/to/your/accuracy_loss_plot.png" width="600">

## 🧪 Try It Out

```python
predict_news("Breaking: Scientists discover new planet in our solar system")
# Output: Prediction: Fake (confidence: 0.00)
