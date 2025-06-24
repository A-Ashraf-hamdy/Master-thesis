# A Comparative Study of Surrogate Models of Floating Renewable Energy Devices – Master's Thesis

This repository contains all the code, data, and analysis used in the Master's thesis titled **"A Comparative Study of Surrogate Models of Floating Renewable Energy Devices"**, with a focus on the PeWEC wave energy converter.

## 📁 Folder Structure

- **PeWEC_data/**  
  Raw simulation data in `.mat` format.

- **prepared_data/**  
  Processed data Training , Validation and Testing split sets in `.csv` format.

- **Models/**  
  Saved models: the best-performing model from each modeling family.

## 📓 Notebooks

- **EDA.ipynb**  
  Loads `.mat` files, analyzes natural modes of the device, explores training sea states, performs exploratory data analysis (EDA), splits the data, and saves it to `.csv` format.

- **lag_Study-ARX.ipynb**  
  Performs lag study, implements and evaluates the ARX model.

- **XGBoost-NARX.ipynb**  
  Implements and tests the XGBoost-NARX model.

- **NARX Models evaluation.ipynb**  
  Post-processing of ARX and XGBoost-NARX results for evaluation and model selection.

- **LSTM.ipynb**  
  Implements and tests the LSTM model.

- **Comparison.ipynb** and **Comparison-2.ipynb**  
  Post-processing and comparative analysis of all surrogate model results.

## 📌 Author

Abdelrahman Gomaa  
Master in Renewable Energy in the Marine Environment (REM+)

---

Feel free to explore, reproduce the results, or build upon this work.
