#### Name - Yashraj Ramdas Chavan
#### Roll no. - DA25M031
#### Assignment 5 - Data Analytics Lab ( Da5401) JUL-NOV 2025 
# DA5401 A5: Visualizing Data Veracity Challenges in Multi-Label Classification 
### OBJECTIVE: This assignment aims to deepen your understanding of the challenges in real-world machine learning, specifically in multi-label classification, by utilizing advanced non-linear dimensionality reduction techniques such as t-SNE and Isomap. You will visually inspect the data for issues such as noisy labels, outliers, and hard-to-learn data points, sparking curiosity about data veracity in a biological context.


## 📌 Contents
- **Part A:** Data preprocessing and label selection  
- **Part B:** Non-linear dimensionality reduction  
  - **t-SNE:** Tested multiple perplexity values and finalized **perplexity = 75**  
  - **Isomap:** Tested multiple neighborhood sizes and finalized **n_neighbors = 100**  
- **Part C:** Analysis of data veracity issues (noisy labels, outliers, hard-to-learn samples)  
- **Comparisons:** Detailed discussion of t-SNE vs. Isomap, global vs. local structure preservation  

---

## 🔑 Key Results
- **t-SNE (perplexity = 75):** Best trade-off between local and global structure, revealed noisy labels, outliers, and complex clusters.  
- **Isomap (n_neighbors = 100):** Preserved global manifold geometry with smooth embeddings and interpretable class separations.  
- **Data Veracity:** Identified noisy/ambiguous samples, rare outliers, and mixed regions that make classification difficult.  

---

## 📂 Files
- `DALabA5.ipynb` → Completed notebook with explanations, visualizations, and justifications  
- Supporting plots and results embedded inside the notebook  

---
