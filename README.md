# BRCA1 Mutation Signature Clustering & Visualization

This project explores **mutation signature profiles** from cancer samples using **unsupervised machine learning** techniques. The goal is to uncover hidden patterns in the mutation data, with a focus on identifying how **BRCA1-related** samples cluster compared to others.

---

## Project Summary

We use mutation signature data (numeric features representing how DNA is mutated in tumor samples) and apply:

- **KMeans clustering** to group samples with similar mutation patterns.
- **Principal Component Analysis (PCA)** to reduce the data to 3 dimensions for visualization.
- **3D plotting with Plotly** to explore and highlight how BRCA1-associated samples behave.

This type of analysis is useful in **cancer genomics research**, especially when studying tumor subtypes and mutation-driven disease mechanisms.

---

## Techniques Used

| Technique | Purpose |
|----------|---------|
| **KMeans Clustering** | Automatically groups similar mutation profiles |
| **PCA (Principal Component Analysis)** | Reduces high-dimensional mutation data into 3D space |
| **Plotly 3D Visualization** | Interactive plots of clusters and BRCA1 sample highlights |
| **Sample Filtering** | Highlights specific samples associated with BRCA1 mutation types |

---

## Tools & Libraries

- Python
- `pandas`, `numpy`
- `sklearn` (for PCA and clustering)
- `plotly` (for interactive visualization)
- `matplotlib`, `seaborn`

---

## File Overview

| File | Description |
|------|-------------|
| `BRCA1_Mutation_Signature_Clustering.ipynb` | Main notebook containing data analysis and visualization |
| `data.csv` (not included) | Expected input: numeric mutation signature data with optional sample IDs or BRCA1 labels |
| `README.md` | Project documentation |

---

## Sample Output

- Interactive 3D scatterplots of clustered samples  
- Color-coded groups by KMeans
- Highlighted BRCA1-related samples for pattern detection

---

## Future Ideas

- Apply other clustering methods (e.g., DBSCAN or Agglomerative)
- Integrate clinical metadata for deeper analysis
- Visualize results alongside gene expression or variant data

