# stanford-rna-3d-folding-2025
My solution for the Stanford RNA 3D Folding Challenge 2025, focusing on predicting the 3D structure of RNA sequences using deep learning techniques.


## 🏆 Competition Overview
In this competition, we aim to predict the full 3D structure of RNA molecules from their sequences, helping to advance RNA-based medicine and biotechnology.

- **Goal:** Predict (x, y, z) coordinates of the C1' atom for each residue across 5 models.
- **Evaluation Metric:** TM-Score (higher is better).

[Link to the competition page](https://www.kaggle.com/competitions/stanford-rna-3d-folding)

---

## 🛠️ Project Structure
```bash
📦 stanford-rna-3d-folding-2025
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┣ 📜 rna-3d-folding.ipynb
 ┗ 📂 src/
     ┣ 📜 model.py
     ┣ 📜 utils.py
     ┗ 📜 data_loader.py
