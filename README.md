**GitHub Project Description: Fundamentals of Machine Learning in Data Science**
## Project Title: Crime Prediction in Vancouver

### Abstract:
In response to the rising concerns about crime, this project focuses on predicting crime behavior and locations in Vancouver using historical crime data. Through data analysis and machine learning models, we aim to identify patterns and make predictions regarding the types of crimes likely to occur and their probable locations. The project involves exploratory data analysis, data wrangling, model planning, implementation, and results interpretation.

### I. Introduction and Discovery:
The dataset, obtained from the Vancouver Police Department, provides information on crime types, time of occurrence, and locations. Privacy measures have been taken to protect individuals' identities, and data interpretation considers the time of the offense, not just the reporting time. Initial assumptions about crime characteristics are made, including correlations with time, season, and specific locations.

### II. Data Wrangling and Transformation:
The original dataset, consisting of 830,165 rows and 10 columns, undergoes data wrangling and transformation. Crimes are labeled, and the dataset is cleaned for analysis.

### III. Exploratory Data Analysis:
Correlation analysis is performed, and a heatmap is generated to identify features relevant to crime types. The geographical distribution of crimes is visualized using the folium library, focusing on the most prevalent crime type: Theft from Vehicle.

### IV. Model Planning:
Crime type prediction models are designed using Logistic Regression, Gaussian Naive Bayes, Decision Tree Classifier, and Artificial Neural Network algorithms. A combination of RobustScaler method and classifiers aims to enhance model accuracy.

### V. Model Implementation and Results Interpretation:
1. **Crime Prediction Model:**
   - Logistic Regression, Gaussian Naive Bayes, and Decision Tree Classifier models are used.
   - Artificial Neural Network algorithms with various hidden layer combinations are explored.
   - Model accuracy is below 43%, indicating unsuitability for prediction.

2. **Hotspots Prediction Model:**
   - Crime hotspot prediction models, including Logistic Regression, K-Nearest Neighbors, Gaussian Naive Bayes, and Random Forest Classifier, are implemented.
   - Naive Bayes model shows the highest accuracy in predicting crime hotspots.

### VI. Out-of-sample Predictions:
The crime prediction models exhibit low accuracy, prompting a focus on the hotspot prediction model for out-of-sample data. The Naive Bayes model demonstrates exceptional performance in predicting crime hotspots.

### VII. Concluding Remarks:
Data cleanup, analysis, and modeling have provided insights into crime patterns in Vancouver. Identification of high-crime areas and trends, such as the prevalence of Theft from Vehicles, was achieved. While crime prediction models fell short of expectations, the hotspot prediction model, particularly using the Gaussian Naive Bayes algorithm, displayed promising accuracy for crime prevention and control.

---
### Repository Contents:
1. **Data:** Contains the raw and cleaned datasets used in the analysis.
2. **Notebooks:** Jupyter notebooks detailing the step-by-step process of data analysis, model planning, and implementation.
3. **Visualizations:** Visual representations of data analysis, including heatmaps and geographical crime distributions.
4. **Models:** Code and information related to the implemented machine learning models.
5. **Results:** Documentation on model results, including accuracy scores, classification reports, and confusion matrices.

### Instructions for Reproduction:
1. Clone the repository.
2. Install required libraries using `pip install -r requirements.txt`.
3. Navigate to the 'Notebooks' directory and run the Jupyter notebooks in sequential order.

### Dependencies:
- Python 3.x
- Jupyter Notebooks
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, TensorFlow, Keras
- Folium

### Contributions:
Contributions, bug reports, and suggestions are welcome. Please follow the [contribution guidelines](CONTRIBUTING.md).

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments:
Special thanks to the Vancouver Police Department for providing the dataset and the open-source community for valuable insights and tools.

---
