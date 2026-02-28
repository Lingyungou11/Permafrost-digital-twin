# Permafrost Digital Twin (Review Version)

This repository contains the code used in the study:  
**"Physics-Informed Digital Twin for Predicting Permafrost Thermodynamic Characteristics under an Embankment Road in Utqiaġvik, Alaska"**

The code implements a **Differentiable Modeling (DM)**-based digital twin framework for permafrost temperature prediction, parameter inversion, and thermodynamic property estimation.  

---

## 📂 Repository Structure

- **BS_model/**  
  Baseline model (BM) implementation, based on differentiable modeling.

- **UP_1/**  
  Updated model using sequential data assimilation (UM1).

- **UP_2/**  
  Updated model using sequential data assimilation (UM2).

---

## 🛠 Requirements

- Python 3.9+  
- Required packages: `numpy`, `pandas`, `matplotlib`, `scipy`, `torch`, `jupyter`

---

## ▶ How to Run

1. Download the repository: Click the green **Code** button → **Download ZIP**  
2. Unzip to a local folder.  
3. Run Jupyter Notebooks in the respective folders.  

---

## 📌 Citation

If you use this code, please cite:

Gou, L., M. Xiao*, T. Zhu, E. Martin, Z. Wang, G. Santos, D. Nicolsky, and X. Ji. 2026. Physics-Informed Digital Twins for Predicting Arctic Permafrost Thermodynamics. Journal of Geophysical Research: Earth Surface, Under
Review.

---

## 📄 Notes

- Please do not redistribute without permission from the authors.  
- The code may require specific input datasets (DTS, DAS, laboratory measurements), which are included here only for peer-review purposes.

---

## License
This project is licensed under the MIT License.

