Principal Component Analysis (PCA) on Iris Dataset 🧪
A Jupyter notebook implementation of Principal Component Analysis (PCA) applied to the Iris dataset — demonstrating dimensionality reduction, visualization, and result interpretation.

📂 Repository Contents
PCA on Iris.ipynb
Notebook that:

Loads the Iris dataset

Standardizes features

Computes covariance matrix

Performs eigen decomposition

Selects top principal components

Projects data onto a lower-dimensional space

Visualizes results in 2D and 3D scatter plots

🎯 Key Features
Step-by-step PCA workflow
Easy-to-follow structure, useful for learning and teaching.

Visualizations
Scatter plots showing how PCA separates different Iris species.

Explained variance output
Shows how much information each principal component retains.

🧩 Prerequisites
Python 3.7+

Anaconda recommended

Jupyter Notebook

📦 Installation
Clone the repo:


git clone https://github.com/srilasya-s/Principal-Component-Analysis.git
cd Principal-Component-Analysis
Create and activate a conda environment:


conda create -n pca-env python=3.9
conda activate pca-env
Install required packages:

pip install numpy pandas matplotlib seaborn scikit-learn
🚀 Run the Notebook
Launch Jupyter Notebook:

jupyter notebook
Then open PCA on Iris.ipynb and run all cells to reproduce the PCA process and visualizations.

📊 Results Overview
Variance explained: Understanding how many components capture most of the data’s variability.

2D scatter: Iris species clearly separated.

Optional 3D plots: Includes first three components for richer insight.

🛠️ Extending the Notebook
Try enhancing by:

Applying PCA to different datasets (e.g., Wine, Digits)

Adding interactive biplots using Plotly

Building a full pipeline with scikit-learn’s PCA() class

Experimenting with data scaling/preprocessing techniques

📚 Resources & References
[Wikipedia: Principal Component Analysis] 


“A Tutorial on Principal Component Analysis” by Shlens 

Practical examples and PCA theory (e.g., GeeksforGeeks) 
geeksforgeeks.org

📛 License
This project is open-source and available under the MIT License — feel free to use, modify, and adapt!

✨ Author
Sri Lasya S.
