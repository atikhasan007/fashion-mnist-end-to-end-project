# 👗 Fashion MNIST Image Classifier (Streamlit + TensorFlow)

This project is a **Deep Learning based Fashion Item Classifier** built using **TensorFlow/Keras** and deployed with **Streamlit**.  
The application allows users to upload an image and predict the fashion item category.

---

## 🚀 Features

- Upload an image (`jpg`, `jpeg`, `png`)
- Automatic image preprocessing
- Real-time prediction
- Interactive web interface using Streamlit
- Deep learning model for classification

---

## 🧠 Model Classes

The model predicts one of the following categories:

1. T-shirt / top  
2. Trouser  
3. Pullover  
4. Dress  
5. Coat  
6. Sandal  
7. Shirt  
8. Sneaker  
9. Bag  
10. Ankle boot  

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- NumPy
- Pillow (PIL)

---

## 📂 Project Structure

```
fashion-mnist-classifier
│
├── app.py
├── README.md
│
├── trained_model
│   └── trained_fashion_mnist_model.h5
│
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/atikhasan007/fashion-mnist-end-to-end-project.git
```

Go to the project directory:

```bash
cd fashion-mnist-end-to-end-project
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Run the Streamlit app:

```bash
streamlit run app.py
```

The app will open in your browser.

---

## 📸 How It Works

1. Upload an image.
2. The image is resized to **28×28 pixels**.
3. Converted to **grayscale**.
4. Pixel values are **normalized**.
5. The trained model predicts the fashion category.
6. The prediction result is displayed on the interface.

---

## 📌 Future Improvements

- Improve model accuracy
- Add better UI design
- Deploy the app on **Streamlit Cloud**
- Support more image datasets

---

## 👨‍💻 Author

**Md Atik Hasan**  
BSc in Computer Science  
Interested in **AI, Machine Learning, and Data Science**
