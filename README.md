# Mlops-through-mlflow-using-Deep-learning-model

# 🚀 Deep Learning Experiment Tracking with MLflow

## 📖 Description

This project focuses on building and managing deep learning models while tracking experiments using MLflow. It demonstrates how to monitor model performance, log parameters, and compare multiple training runs efficiently.

The goal is to simplify the machine learning lifecycle by integrating experiment tracking, model management, and reproducibility in one place.

---

## 🎯 Features

* 📊 Track experiments (accuracy, loss, etc.)
* ⚙️ Log hyperparameters (learning rate, epochs, batch size)
* 🧠 Train deep learning models
* 💾 Save and load trained models
* 📈 Compare multiple experiment runs
* 🔍 Visualize results using MLflow UI

---

## 🛠️ Technologies Used

* Python
* TensorFlow / PyTorch
* MLflow
* NumPy
* Pandas
* Matplotlib

---

## 📂 Project Structure

```
project/
│── data/              # Dataset files
│── models/            # Saved models
│── notebooks/         # Jupyter notebooks
│── src/               # Source code
│   ├── train.py       # Model training script
│   ├── utils.py       # Helper functions
│── mlruns/            # MLflow tracking data
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/deep-learning-mlflow.git
cd deep-learning-mlflow
```

2. Install dependencies:

```
pip install -r requirements.txt
```

---

## 🚀 Usage

### ▶️ Train the Model

```
python src/train.py
```

### 📊 Start MLflow UI

```
mlflow ui
```

Then open in browser:

```
http://localhost:5000
```

---

## 📊 MLflow Integration

This project uses MLflow to:

* Log parameters:

```
mlflow.log_param("learning_rate", 0.001)
mlflow.log_param("epochs", 10)
```

* Log metrics:

```
mlflow.log_metric("accuracy", accuracy)
mlflow.log_metric("loss", loss)
```

* Save model:

```
mlflow.pytorch.log_model(model, "model")
```

or

```
mlflow.tensorflow.log_model(model, "model")
```

---

## 📷 Results

MLflow UI allows:

* Comparing different runs
* Visualizing performance metrics
* Selecting best model

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

