# Donut Biomarker Classification 🍩🧪

This project simulates biomarker readings from lab animals in a toxicology study.  
Two rings of data (healthy vs. affected) are generated using NumPy, visualized with Matplotlib,  
and exported for machine learning modeling.

## 📊 Dataset
- `x1`, `x2`: synthetic biomarkers  
- `y`: label (0 = healthy, 1 = affected)  
- `x1_squared`, `x2_cubed`, `x1_times_x2`: engineered features  

The dataset is stored in `donut_dataset.csv`.

## ⚙️ Requirements
- NumPy  
- Pandas  
- Matplotlib  

(Install with `pip install -r requirements.txt` if you create one)

## 🚀 Usage
1. Open `donut_biomarker_classification.ipynb` in Jupyter Notebook / JupyterLab  
2. Run all cells to generate dataset and plots  
3. Check the output CSV (`donut_dataset.csv`)

## 📂 Project Structure
