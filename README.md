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



## Manual Classification Accuracy

Applying manual classification rules based on feature analysis yielded an impressive accuracy of 95%, underscoring the dataset's distinct species characteristics.

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



