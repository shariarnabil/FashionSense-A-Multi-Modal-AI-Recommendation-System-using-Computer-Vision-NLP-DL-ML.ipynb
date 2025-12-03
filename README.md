# **Fashion Item Prediction Demo**

This project demonstrates a **multi-modal machine learning application** combining:

- **Computer Vision (CNN)** – image classification of fashion items  
- **Tabular ML (Random Forest)** – prediction based on features like price and popularity  
- **Natural Language Processing (Transformers)** – sentiment analysis of user reviews  

Users can interact with the models through **Jupyter/Colab widgets** to upload images, enter tabular data, and write reviews.

---

## **Table of Contents**

- [Features](#features)  
- [Fashion Labels](#fashion-labels)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Example](#example)  
- [Dependencies](#dependencies)  
- [License](#license)  

---

## **Features**

### **1. CNN on Fashion MNIST**
- A Convolutional Neural Network trained on the **Fashion MNIST dataset**.  
- Classifies images into **10 categories**:

T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

---

### **2. Random Forest Tabular Model**
- Predicts fashion item categories from **tabular features**:  
  - Price  
  - Rating  
  - Popularity  

---

### **3. NLP Sentiment Analysis**
- Uses **DistilBERT** for sentiment analysis of user reviews.  
- Outputs:  
  - `POSITIVE`  
  - `NEGATIVE`  

---

### **4. Interactive Widgets**
- Upload a fashion image  
- Enter price, rating, and popularity  
- Write a text review  
- Click **Predict** to see all model predictions  

---

## **Fashion Labels**

| Label Index | Category       |
|------------:|---------------|
| 0           | T-shirt/top   |
| 1           | Trouser       |
| 2           | Pullover      |
| 3           | Dress         |
| 4           | Coat          |
| 5           | Sandal        |
| 6           | Shirt         |
| 7           | Sneaker       |
| 8           | Bag           |
| 9           | Ankle boot    |

---

## **Installation**

1. Clone the repository:

git clone <repo-url>
cd <repo-folder>

markdown
Copy code

2. Install dependencies:

pip install tensorflow numpy scikit-learn Pillow torch transformers ipywidgets

yaml
Copy code

---

## **Usage**

1. Open the Jupyter notebook or Colab file.  
2. Use the interactive widgets to:  
   - Upload an image  
   - Set price, rating, and popularity  
   - Write a short review  
3. Click **Predict** to get:  
   - CNN image prediction  
   - Random Forest tabular prediction  
   - NLP sentiment analysis  

---

## **Example**

| Input Type       | Example Input                     | Model Prediction |
|-----------------|----------------------------------|----------------|
| Image            | sneaker.png                       | Sneaker        |
| Tabular Features | Price=50, Rating=4, Popularity=80| Sneaker        |
| Review Text      | "Great shoes, very comfortable!" | POSITIVE       |

---

## **Dependencies**

- tensorflow>=2.0  
- numpy  
- scikit-learn  
- Pillow  
- torch  
- transformers  
- ipywidgets  

---

## **License**

This project is open-source and licensed under the **MIT License**.

---

## **Acknowledgements**

- [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)  
- [Hugging Face Transformers](https://huggingface.co/transformers/)  
- TensorFlow & Keras for deep learning support  


