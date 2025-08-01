# AI-Powered-Drug-Discovery-with-Deep-Learning# 
This project leverages deep learning and cheminformatics to predict the **IC50 values** (a measure of bioactivity) of chemical compounds. It uses **SMILES strings**, processes them into molecular fingerprints using **RDKit**, and trains a regression model with **TensorFlow/Keras** to enable **virtual screening** of new drug candidates.

---

## 🚀 Project Objectives

- Predict **IC50** values for compounds to evaluate drug potency.
- Use **RDKit** to generate fingerprint features from SMILES.
- Train a robust deep learning model using **TensorFlow**.
- Evaluate performance with **cross-validation** techniques.
- Predict bioactivity on **new, unseen molecules**.

---

## 🧪 Technologies & Libraries Used

| Area              | Tools / Libraries                            |
|-------------------|-----------------------------------------------|
| Deep Learning     | TensorFlow / Keras                            |
| Cheminformatics   | RDKit                                         |
| Data Handling     | Pandas, NumPy                                 |
| Evaluation        | Scikit-learn                                  |
| Visualization     | Matplotlib, Seaborn                           |
| Dataset Source    | [ChEMBL](https://www.ebi.ac.uk/chembl/)       |
| Environment       | Google Colab                                  |

---

## 📂 Project Structure📁
 ai-drug-discovery/
 
 |

📜 ai_drug_model.ipynb # Google Colab-compatible notebook

📄 README.md # Project documentation

📁 data/ # Raw and processed dataset files

📁 models/ # Trained model (.h5 or .pkl)

📁 output/ # Predictions for new molecules

📄 LICENSE # MIT License file

---

## 🔍 How It Works

1. **Load Data**: Dataset with SMILES + IC50 values from ChEMBL.
2. **Feature Engineering**: Convert SMILES into Morgan fingerprints using RDKit.
3. **Model Training**: Deep Neural Network using TensorFlow/Keras for regression.
4. **Evaluation**: Use K-Fold Cross-Validation + metrics like MSE, MAE.
5. **Predict New Molecules**: Input new SMILES to estimate IC50 values.

---

## 📈 Example Results

| SMILES                                  | Predicted IC50 (nM) |
|----------------------------------------|----------------------|
| `CCOC(=O)c1ccc2nc(S(N)(=O)=O)sc2c1`     | 215.4                |
| `CCN(CC)CCCC(C)Nc1nccc2nc(C)nn12`       | 389.9                |

---

## 📊 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score
- Training vs Validation Loss Curves
- Actual vs Predicted Scatter Plots

---

## ✅ Conclusion

This project demonstrates how deep learning and cheminformatics can accelerate **AI-powered drug discovery**. By predicting molecular bioactivity (IC50), researchers can efficiently screen and prioritize compounds, significantly reducing the time and cost associated with traditional drug development. The model is robust, scalable, and can be further extended to include ADMET filtering, molecular docking, or Graph Neural Networks (GNNs).

---

## 🔮 Future Extensions

- ✅ Integrate **ADMET filtering** for drug-likeness checks
- ✅ Add **Graph Neural Networks (GNNs)** for improved structure understanding
- ✅ Apply **Molecular Docking** for target-ligand interaction analysis
- ✅ Build an interactive UI using **Streamlit**

---

## 👤 Author

**Vikas Purbia**  
*AI & Machine Learning Enthusiast | Deep Learning | Drug Discovery | Data Science*  
[GitHub](github.com/VIKAS-PURBIA) • [LinkedIn](linkedin.com/in/vikas-purbia-10734432a  ) • [Email](vikaspurbia123@gmail.com)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

