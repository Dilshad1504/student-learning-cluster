# Clustering Students Based on Study Methods Using KMeans

This project applies **KMeans Clustering** to group students based on their study methods. It uses a dataset containing students' learning behavior attributes and aims to classify them into meaningful clusters for further analysis and insights.

## Objective

To implement an unsupervised machine learning technique (KMeans) to:
- Analyze patterns in student study methods.
- Group students into clusters based on similarities in their learning habits.
- Visualize the clustering results for better interpretability.

## Dataset

The dataset (`student_methods.csv`) contains various numeric features representing different study behaviors of students. Ensure the dataset is numeric or preprocessed accordingly before applying KMeans.

## Technologies Used

- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

## Methodology

1. **Data Loading** – Load and preview the dataset.
2. **Preprocessing** – Select only numeric columns for clustering.
3. **Elbow Method** – Determine the optimal number of clusters using WCSS.
4. **KMeans Clustering** – Apply KMeans algorithm with the chosen cluster number.
5. **Visualization** – Scatter plot of clustered data using the first two features.

## Output

- **Elbow Plot** – To identify the optimal number of clusters.
- **Clustered Dataset** – Students assigned to different clusters.
- **Scatter Plot** – Visual visualization of clustering using 2D projection.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/student-study-clustering.git
    cd student-study-clustering
    ```

2. Install the required libraries:
    ```bash
    pip install pandas scikit-learn matplotlib seaborn
    ```

3. Run the script in your preferred Python environment (e.g., Jupyter Notebook, Google Colab, or directly with Python).

4. Make sure your `student_methods.csv` file is in the correct path (adjust if needed).

## Sample Visualization

*(Insert screenshots of the Elbow Plot and Cluster Scatter Plot here)*

## References

- [Scikit-learn Documentation](https://scikit-learn.org)
- [Matplotlib Documentation](https://matplotlib.org)
- [Seaborn Documentation](https://seaborn.pydata.org)

---

**Author:** Mohammad Dilshad  
**Date:** April 2025

