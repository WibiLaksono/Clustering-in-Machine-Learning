
# Clustering in Machine Learning

Welcome! 🎉  
This repository contains experiments and implementations of clustering techniques in **Machine Learning**, such as **K-Means** and **DBSCAN**. It's designed for those who want to understand how unsupervised learning works in practice, especially in the context of clustering.

Whether you're a beginner or an enthusiast in the world of machine learning, we hope this repository helps you explore clustering techniques more deeply. 💡

---

## 📁 Project Structure

```
Clustering-in-Machine-Learning/
│
├── DBSCAN/
│   ├── experiment/        # Main DBSCAN experiments
│   └── testing/           # Testing and validation for DBSCAN
│
├── K-means/               # K-Means clustering experiments
│
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## ⚙️ Setup Instructions (Using Jupyter Notebook)

To run the experiments locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/WibiLaksono/Clustering-in-Machine-Learning.git
cd Clustering-in-Machine-Learning
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate        # For macOS/Linux
venv\Scripts\activate           # For Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any `.ipynb` file inside the `DBSCAN/experiment/`, `DBSCAN/testing/`, or `K-means/` folders to explore and run the code interactively.

---

## 📦 Main Dependencies

This project uses the following Python libraries:

- `ucimlrepo` – For loading datasets from UCI Machine Learning Repository  
- `numpy`, `pandas` – Data handling and manipulation  
- `matplotlib`, `seaborn` – Data visualization  
- `scikit-learn` – Clustering algorithms and evaluation metrics  
- `jupyter` – Interactive environment for running notebooks

All dependencies are listed in the [`requirements.txt`](./requirements.txt) file.

---

## 📊 Evaluation Metrics Used

Some clustering evaluation metrics implemented in this project include:

- **Silhouette Score**  
- **Davies-Bouldin Score**  
- **Calinski-Harabasz Score**  
- **Adjusted Rand Index**  
- **Normalized Mutual Information (NMI)**

These help evaluate clustering quality based on different aspects like compactness, separation, and similarity to ground truth.

---

## 🤝 Contributions

Feel free to contribute!  
If you have an idea for a new experiment, algorithm, or improvement, open an issue or submit a pull request. Collaboration is always welcome! 🚀

---

## ✨ Closing Note

Thanks for visiting this repository!  
We hope it becomes a valuable resource for your journey into machine learning, especially in understanding clustering algorithms.

Warm regards,  
**Wibi Laksono**
