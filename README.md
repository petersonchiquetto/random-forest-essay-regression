# 🎓 Random Forest Essay Regression

This project is a machine learning model built to predict essay scores from the **2018 ENEM (Brazilian national high school exam)** using a **Random Forest Regressor**.

It uses demographic features and scores from other subjects to estimate a student's performance in the writing section.

## 📁 Dataset

- Source: Public sample from ENEM 2018
- Format: CSV
- Encoding: Latin-1
- URL: [ENEM 2018 Sample Dataset](https://raw.githubusercontent.com/guilhermesilveira/enem-2018/refs/heads/master/MICRODADOS_ENEM_2018_SAMPLE_43278.csv)

## 🔧 Features Used

- `NU_IDADE` (Age)
- `TP_SEXO` (Gender)
- `TP_ESTADO_CIVIL` (Marital status)
- `TP_COR_RACA` (Race/Color)
- `Q006` (Family income)
- `NU_NOTA_CN`, `NU_NOTA_CH`, `NU_NOTA_LC`, `NU_NOTA_MT` (Scores in other subjects)

## 🛠️ Technologies

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🚀 How It Works

1. **Load the dataset**
2. **Select relevant features**
3. **Filter and clean the data**
4. **Encode categorical variables**
5. **Split dataset into train/test**
6. **Train a RandomForestRegressor**
7. **Evaluate using MSE and R²**
8. **Visualize predictions and feature importance**

## 📊 Example Output

- Mean Squared Error (MSE): *[value depends on run]*
- R² Score: *[value depends on run]*

## ✅ Usage

To run the notebook:

1. Clone this repository:
   ```
   git clone https://github.com/petersonchiquetto/random-forest-essay-regression.git
  ```


2. Install dependencies (optional):

   ```   pip install -r requirements.txt
```
3. Open and run `random_forest_essay_regression.ipynb` in Jupyter or Google Colab.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Made with 💡 by **Peterson Chiquetto**

[GitHub Profile](https://github.com/petersonchiquetto)
