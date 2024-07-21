# Customer Segmentation Analysis Using K-Means Clustering for Enhanced Marketing Strategies

## Project Overview
This project utilizes K-Means Clustering, an unsupervised machine learning technique, to perform customer segmentation. The analysis is based on a dataset specifically designed for learning the concepts of market basket analysis. By segmenting customers according to their annual income, spending score, and age, this project aims to provide insights that can help in crafting targeted marketing strategies.

## About Dataset
This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis . I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.
- More here: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data

## Table of Contents
- [Installation](#installation)
- [Data Description](#data-description)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results and Discussion](#results-and-discussion)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this project, you will need Python and the following Python libraries installed:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

You can install these packages using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Data Description
The dataset used in this project is crafted for the purpose of understanding customer segmentation (market basket analysis). It includes the following fields:
- **CustomerID**: Unique identifier for the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual Income of the customer in thousand dollars
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature

## Usage
To run this project, simply clone the repository and execute the Jupyter notebook:
```bash
git clone https://github.com/Manuel-ventura/Customer-Segmentation-Analysis-Using-K-Means-Clustering-for-Enhanced-Marketing-Strategies.git
cd Customer-Segmentation-Analysis-Using-K-Means-Clustering-for-Enhanced-Marketing-Strategies
jupyter notebook k-means-clustering-mall-customer.ipynb
```

## Methodology
The project follows these steps:
1. **Data Preprocessing**: Handling missing values, renaming columns for easier access.
2. **Exploratory Data Analysis (EDA)**: Visualizing pairplots and distributions to understand relationships between features.
3. **Optimal Cluster Determination**: Using the elbow method to determine the optimal number of clusters.
4. **K-Means Clustering**: Applying K-Means algorithm to segment customers.
5. **Visualization**: Visualizing the clusters in various scatter plots and 3D plots to interpret the segments effectively.

## Results and Discussion
The K-Means clustering algorithm helped identify distinct groups within the customer data, based on their spending habits and demographic information. The analysis provides insights that can guide the development of targeted marketing strategies to enhance customer engagement and profitability.

## Contributing
Contributions to this project are welcome. Please ensure to update tests as appropriate.

## License
Distributed under the MIT License. See `LICENSE` for more information.
