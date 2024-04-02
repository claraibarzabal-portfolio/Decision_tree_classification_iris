# Decision Tree Classification Analysis on Iris Dataset

A thorough exploration and analysis of the Iris dataset to classify species based on sepal and petal measurements. This project demonstrates data preprocessing, conversion, and a simple decision-making approach to predict species with remarkable accuracy.

## Dataset Overview

The dataset, `Iris.csv`, used in this analysis is based on the Iris dataset available on Kaggle. It comprises observations on sepal length, sepal width, petal length, petal width, and species for 150 Iris flowers. You can access the dataset through this [Kaggle link](https://www.kaggle.com/datasets/uciml/iris).

For convenience, a copy of the dataset is included in the "data" folder of this GitHub repository.

## Preprocessing Highlights

### Before Conversion

Initially observed data with locale-specific decimal notation (commas), not suited for numerical operations in Python:

  SepalLengthCm: 4,9            
  
### After Conversion

Converted string values to float, facilitating accurate numerical analysis and modeling:

   SepalLengthCm: 4.9

## Feature Engineering and Manual Classification

### Decision Tree for Manual Classification

The classification was carried out by constructing a decision tree that leverages logical conditions derived from the dataset's features. The tree operates as follows:

- **If `PetalLength <= 2`:**
  - **Classify as Setosa**
- **Else if `PetalLength > 2.5`:**
  - **If `PetalWidth >= 1.75`:**
    - **If `SepalLength <= 5`:**
      - **Classify as Versicolor**
    - **Else if `SepalLength > 5`:**
      - **Classify as Virginica**
  - **Else if `PetalWidth < 1.75`:**
    - **Classify as Virginica**

### Results from Manual Classification

The application of this decision tree for manual classification yielded an accuracy rate of **95%**. This high level of accuracy underscores the distinct morphological features that differentiate each Iris species, demonstrating the effectiveness of manual classification based on logical rules.


## How to Run This Analysis

1. **Clone or Download the Repository**: Ensure you have access to the `Iris.csv` dataset located in the "data" folder.
2. **Set Up Your Environment**: Verify that Python, along with pandas, matplotlib, seaborn, and scikit-learn, is installed on your machine.
3. **Open the Notebook**: Navigate to the `Decision_Tree_Classification_Iris.ipynb` notebook. This can be done using Jupyter Lab or Jupyter Notebook.
4. **Execute the Notebook**: Run each cell sequentially to reproduce the analysis and view the results.

## Conclusion

This analysis not only highlights the preprocessing steps required to prepare data for analysis but also showcases the power of simple decision-making algorithms in classifying species with high accuracy. The approach and methodologies used here can serve as a template for similar data analysis tasks.

## Technologies Used

- **Python:** The main programming language used for conducting the analysis. It offers extensive support for data manipulation and analysis.

- **Pandas:** Utilized for reading the dataset and performing data manipulation tasks. It's a powerful library that offers data structures and operations for manipulating numerical tables and time series.

Given the scope of this analysis, focusing on data preprocessing and manual classification, Pandas was sufficient to handle all data-related operations.

## Acknowledgements

Special thanks to [Kaggle](https://www.kaggle.com/) for providing the Iris dataset, enabling this exploratory analysis and classification project.



