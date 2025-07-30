# customer-segmentation-clustering-models

This project applies different clustering techniques on a customer dataset to identify meaningful customer segments based on Age, Annual Income, and Spending Score.

## 📁 Files Included

- `clustering_analysis.py` – Main Python script containing all the clustering and visualization logic.
- `customers.csv` – Dataset containing customer details.
- `README.md` – This file.

## 🧪 Algorithms Used

- **K-Means Clustering**
- **DBSCAN**
- **Hierarchical Clustering**

## 📊 Evaluation Metric

- **Silhouette Score** was used to evaluate clustering performance.

### Silhouette Scores:
- K-Means: `0.431`
- DBSCAN: `0.188`
- Hierarchical Clustering: `0.361`

## 📌 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/ZuveriaMalek/customer-segmentation-clustering-models
    ```
   ```bash
    cd customer-segmentation-clustering-models
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:
    ```bash
    python clustering_analysis.py
    ```

