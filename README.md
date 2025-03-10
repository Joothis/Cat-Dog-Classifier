# 🐱🐶 Cat-Dog Classifier

A **Deep Learning-based** binary classifier that differentiates between images of cats and dogs using Convolutional Neural Networks (CNNs).

## 🗂 Dataset
We use publicly available cat and dog image datasets:  

| Dataset | Description | Source |
|---------|-------------|--------|
| **Kaggle Dogs vs. Cats** | 25,000 labeled images of cats and dogs | [Kaggle](https://www.kaggle.com/datasets/chetankv/dogs-cats-images) |
| **Oxford Pets Dataset** | 37 pet breeds with annotated images | [Oxford Pets](https://www.robots.ox.ac.uk/~vgg/data/pets/) |
| **Stanford Dogs Dataset** | 20,580 dog images across 120 breeds | [Stanford Dogs](http://vision.stanford.edu/aditya86/ImageNetDogs/) |

## 🔧 Installation
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/Cat-Dog-Classifier.git
cd Cat-Dog-Classifier
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook  
```bash
jupyter notebook
```
Open **`cat_dog_classifier.ipynb`** and run the cells.

## 📜 Model Details
- **Architecture:** CNN (Convolutional Neural Network)  
- **Framework:** TensorFlow / Keras  
- **Optimizer:** Adam  
- **Loss Function:** Binary Cross-Entropy  
- **Activation Functions:** ReLU (hidden layers), Sigmoid (output layer)  
- **Training Strategy:** Data augmentation, dropout, early stopping  

## 🚀 How to Use
1. Run the Jupyter Notebook.
2. Train the model using the dataset.
3. Test it by providing a new cat/dog image.

### Example Usage
```python
predict_image("test_image.jpg")
```
✅ Output:
```
Prediction: Cat 🐱
```

## 📊 Performance
| Metric  | Value |
|---------|-------|
| **Accuracy** | 95% |
| **Loss** | 0.05 |
| **Training Time** | ~10 minutes |

## 🖼 Sample Predictions
| Input Image | Prediction |
|-------------|------------|
| ![Cat](images/sample_cat.jpg) | Cat 🐱 |
| ![Dog](images/sample_dog.jpg) | Dog 🐶 |

## 🤝 Contributing
Want to improve this project? Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Added a new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## 📜 License
This project is licensed under the **MIT License**.

## 📩 Contact
📧 Email: joothiswaranpalanisamy2005@gmail.com
📌 GitHub: [Joothis](https://github.com/joothis)
