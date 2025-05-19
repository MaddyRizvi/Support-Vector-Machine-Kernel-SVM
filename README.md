# Kernel SVM Classifier in Python (Google Colab Friendly)

This repository showcases a comparative implementation of Support Vector Machine (SVM) classifiers using both Linear and RBF (Kernel) approaches on the Social Network Ads dataset, illustrating how the RBF kernel effectively captures complex, non-linear patterns that a linear kernel might miss.

## 📌 Project Features

- Simple and clean implementation using `scikit-learn`
- Easily switch between linear and RBF kernels
- Visualization of decision boundaries for training and test sets
- ![Image](https://github.com/user-attachments/assets/36d7d59e-9d29-494d-a00f-253f32074229)
- ![Image](https://github.com/user-attachments/assets/6e57759e-8277-4310-b27c-5e36367b9b55)
- ![Image](https://github.com/user-attachments/assets/341df94b-f260-4871-8f32-2692f0581cda)
- ![Image](https://github.com/user-attachments/assets/d13d9980-dd17-4664-b03e-94f1195b55bf)
- Includes accuracy and confusion matrix evaluation
- Google Colab compatible

## 📁 Files Included

- `support_vector_machine.py` — Implements SVM with a linear kernel
- `kernel_svm.py` — Implements SVM with an RBF (Gaussian) kernel

> 🔁 You can easily switch between `kernel='linear'` and `kernel='rbf'` in the classifier definition to explore both models.

## 🚀 Getting Started on Google Colab

1. Upload or mount the dataset file `Social_Network_Ads.csv`.
2. Open either of the `.py` files in Google Colab or copy the code into a new Colab notebook.
3. Add the following import and classifier line to define your model:

```python
from sklearn.svm import SVC
classifier = SVC(kernel='rbf', random_state=0)  # Or use kernel='linear'
classifier.fit(X_train, y_train)
```

4. Run the cells to train, predict, evaluate, and visualize the classifier.

## 🛠 Requirements

- Python 3.x
- pandas
- matplotlib
- scikit-learn
- numpy

You can install missing libraries using:

```bash
!pip install numpy pandas matplotlib scikit-learn
```

## 📊 Dataset

The dataset used is `Social_Network_Ads.csv`, which contains user information like Age and Estimated Salary along with a target variable indicating purchase behavior.

## 🤝 Contributing

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file to learn how you can contribute to this project.

## 📃 License

This project is open-source and free to use.
