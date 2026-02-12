Task 1: Data Cleaning & Preprocessing

In this project, the Titanic dataset was imported and preprocessed using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

1. Dataset Exploration

* Loaded the dataset using `pandas.read_csv()`
* Checked first few rows using `head()`
* Analyzed structure using `info()` and `dtypes`
* Generated statistical summary using `describe()`
* Identified missing values using `isnull().sum()`

2. Handling Missing Values

* Filled missing values in **Age** using the **median**
* Filled missing values in **Embarked** using the **mode**
* Replaced missing values in **Cabin** with `"Unknown"`

3. Encoding Categorical Features

* Converted categorical features (such as Sex and Embarked) into numerical format using encoding techniques (One-Hot Encoding).

4. Feature Scaling

* Applied **StandardScaler** to numerical features (`Pclass`, `Age`, `SibSp`, `Parch`, `Fare`)
* Standardization ensures features have mean = 0 and standard deviation = 1

5. Outlier Detection and Removal

* Visualized numerical features using **boxplots**
* Detected outliers using the **Interquartile Range (IQR) method**
* Removed data points falling outside acceptable IQR limits

---

The dataset is now cleaned, scaled, and ready for machine learning model training.
