# Clustering and Classification Project

## Overview
This repository demonstrates the implementation of both supervised and unsupervised machine learning techniques using a COVID-19 dataset. The project includes clustering using **DBSCAN** and **KMeans**, as well as classification using **Random Forest** and **Gradient Boosting Classifier** models. Comprehensive evaluations and visualizations are provided to ensure clarity and professional-quality results.

---

## Dataset
The dataset used in this project contains COVID-19 data with the following columns:

- `Date`
- `Location ISO Code`
- `Location`
- `New Cases`
- `New Deaths`
- `New Recovered`
- `New Active Cases`
- `Total Cases`
- `Total Deaths`
- `Total Recovered`
- `Total Active Cases`
- `Location Level`
- `City or Regency`
- `Province`
- `Country`
- `Continent`
- `Island`
- `Time Zone`
- `Special Status`
- `Total Regencies`
- `Total Cities`
- `Total Districts`
- `Total Urban Villages`
- `Total Rural Villages`
- `Area (km2)`
- `Population`
- `Population Density`
- `Longitude`
- `Latitude`
- `New Cases per Million`
- `Total Cases per Million`
- `New Deaths per Million`
- `Total Deaths per Million`
- `Case Fatality Rate`
- `Case Recovered Rate`
- `Growth Factor of New Cases`
- `Growth Factor of New Deaths`

---

## Project Structure

### Unsupervised Learning: Clustering
1. **DBSCAN**
   - Parameters:
     - `eps`: Maximum distance between two samples to be considered as in the same neighborhood.
     - `min_samples`: Minimum number of points required to form a dense region.
   - Evaluation:
     - Silhouette Score
     - Cluster distribution plots
   - Visualization:
     - Scatter plot of clusters based on `Total Cases` and `Total Deaths`.

2. **KMeans**
   - Optimal `k` determination using the Elbow Method.
   - Evaluation:
     - Inertia plots.
     - Silhouette Score.
   - Visualization:
     - Scatter plot of clusters based on `Total Cases` and `Total Deaths`.

### Supervised Learning: Classification
1. **Random Forest Classifier**
   - Hyperparameter tuning using GridSearchCV.
   - Metrics:
     - Accuracy, Precision, Recall, F1-Score.
   - Visualization:
     - Confusion matrix.
     - Feature importance plot.

2. **Gradient Boosting Classifier**
   - Hyperparameter tuning using GridSearchCV.
   - Metrics:
     - Accuracy, Precision, Recall, F1-Score.
   - Visualization:
     - Confusion matrix.
     - Feature importance plot.

---

## How to Use

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Code
1. Preprocess the dataset:
   - Ensure the dataset is in the root directory with the name `covid_19_indonesia_time_series_all.csv`.
2. Execute the scripts:
   - **Clustering Analysis**:
     ```bash
     python clustering_analysis.py
     ```
   - **Classification Analysis**:
     ```bash
     python classification_analysis.py
     ```

---

## Results
### Clustering Results
- **DBSCAN**:
  - Silhouette Score: _[Value will be dynamically calculated]_
  - Visualizations: Cluster distribution scatter plots saved as images.
- **KMeans**:
  - Optimal `k`: _[Value dynamically determined using the Elbow Method]_
  - Silhouette Score: _[Value will be dynamically calculated]_
  - Visualizations: Cluster distribution scatter plots and inertia plots saved as images.

### Classification Results
- **Random Forest Classifier**:
  - Accuracy: _[Dynamic value]_  
  - Precision, Recall, F1-Score: _[Dynamic values]_  
  - Confusion matrix and feature importance visualizations saved as images.

- **Gradient Boosting Classifier**:
  - Accuracy: _[Dynamic value]_  
  - Precision, Recall, F1-Score: _[Dynamic values]_  
  - Confusion matrix and feature importance visualizations saved as images.

---

## Visualizations
All visualizations, including plots for the Elbow Method, cluster distributions, confusion matrices, and feature importance, are saved in the `visualizations` folder.

---

## Contributing
If you would like to contribute, feel free to fork the repository and submit a pull request. Please ensure your contributions adhere to the project's coding standards.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments
Special thanks to the contributors and the open-source community for supporting this project.