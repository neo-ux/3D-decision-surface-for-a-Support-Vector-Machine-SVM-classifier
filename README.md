
# 🎥 3D SVM Decision Boundary Visualization

This project demonstrates how to visualize the decision boundary of a Support Vector Machine (SVM) in **3D** using synthetic classification data. It uses `matplotlib`, `scikit-learn`, and `numpy` for data generation, modeling, and visualization. A rotating animation shows how the decision surface evolves with different viewing angles.

---

## 🧠 What This Project Does

- Generates synthetic 3D classification data using `make_classification`
- Trains an SVM with an RBF kernel on the data
- Plots a 3D decision surface using `matplotlib` and `mpl_toolkits.mplot3d`
- Animates the 3D view to rotate the decision surface

---

## 📦 Dependencies

Ensure you have the following Python libraries installed:

```bash
pip install numpy matplotlib scikit-learn
```

---

## 📁 Files Included

- `svm_3d_visualization.ipynb`: Jupyter Notebook containing the full implementation and animation.
- (Optional) `README.md`: You are reading it!

---

## ▶️ How to Run

1. Open the notebook in Jupyter or any notebook-compatible environment.
2. Run the cells in order. The final cell will render an interactive animation of the decision surface.
3. If animation doesn't render:
   - Use a trusted notebook (not a read-only viewer).
   - Alternatively, view it via [nbviewer](https://nbviewer.org).

---

## ⚠️ Notes

- The animation may hit the `matplotlib` size limit (20MB) in some environments. To fix:

```python
import matplotlib as mpl
mpl.rcParams['animation.embed_limit'] = 50  # increase MB limit if needed
```

- You may also see a font warning for emojis. It doesn't affect the plot functionality.

---

## 🌟 Output Preview

![preview](https://github.com/user-attachments/assets/62c52370-d683-465e-94ca-29d3b345cfa1)


---

## 📜 License

MIT License

---

## 🙋 Author

**Ganesh Shelar**  
Email: shelarganesh131@gmail.com  
GitHub: [neo-ux](https://github.com/neo-ux)  
LinkedIn: [contactganesh7](https://linkedin.com/in/contactganesh7)

---
