# OptiComb: ML for Frequency Comb Prediction  

## 📌 Project Overview  
**OptiComb** is a machine learning project co-developed as part of a Ph.D. research effort to optimize **frequency comb flatness** in optical communication systems. The project leverages **LSTM** and **Feedforward Neural Networks (FNNs)** to predict frequency comb behavior and improve flatness estimation accuracy, thereby enabling faster experimental analysis.  

The developed models demonstrated significant improvements in prediction accuracy, accelerating the analysis of frequency comb dynamics and reducing reliance on time-intensive experimental procedures.  

---

## 🚀 Features  
- Generates RF–DC–frequency datasets programmatically.  
- Integrates experimental power values from `.xlsx` files into frequency datasets.  
- Cleans and preprocesses data (NaN/invalid values filtering, feature engineering).  
- Computes metrics such as **flatness (within 2 dB)** and **frequency line counts**.  
- Implements ML models (**LSTM, Feedforward Neural Network, Random Forest baseline**) for prediction.  
- Provides visualization of training results and prediction outputs.  

---

## 🛠️ Tech Stack  
- **Languages/Libraries:** Python, NumPy, Pandas, Matplotlib  
- **ML/DL Frameworks:** TensorFlow, Keras, scikit-learn  
- **Models Used:**  
  - Feedforward Neural Network (Dense layers)  
  - Long Short-Term Memory (LSTM)  
  - Random Forest (baseline)  

---

## 📂 Project Structure  
```bash
OptiComb/
│──src
    │──Model_trainer.ipynb   # Main Jupyter Notebook 
    │── pm.xlsx              # Experimental dataset with multiple RF2 sheets
│── rf_dc_dataset.csv        # Generated dataset (RF/DC with frequencies)
│── rf_dc_mapped_dataset.csv # Dataset after mapping with experimental data                
│── README.md                # Project documentation
│── Requirements.txt
---

## 📊 Results  
- LSTM and FNN models achieved high accuracy in predicting comb flatness.  
- Predictions closely matched experimental results, validating the effectiveness of the approach.  
- Visualizations highlight both training convergence and real-world prediction performance.  

---

## 📖 Usage  
1. Clone this repository:  
   ```bash
   git clone https://github.com/nisha1904/OptiComb-ML-for-Frequency-Comb-Prediction.git
   cd OptiComb-ML-for-Frequency-Comb-Prediction
2. Open the Jupyter Notebook
    ```bash
    jupyter notebook src/Model_trainer.ipynb

3. Run all cells to:
    Generate datasets
    Preprocess & map experimental data
    Train models (LSTM, FNN, Random Forest)
    Visualize results

📊 Dataset Availability

The experimental dataset (pm.xlsx) contains sensitive research data and is available upon request for academic/research purposes.
If you are interested, please reach out to the author directly.

👤 Author

Nisha Kumari

🎓 Co-developer of the project as part of a Ph.D. research collaboration

📧 Email: nisha1922004@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/nisha-kumari-2964bb212/
