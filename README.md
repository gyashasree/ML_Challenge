# Iris Flower Classification Project

This project aims to classify Iris flowers based on their sepal and petal measurements. The Iris dataset is a popular dataset in machine learning and is commonly used for classification tasks.

## Team Members
### Team Name: 'Tech Musketeers'
- Sangem Jaya Prakash 
- Gundlapalle Yashashree

## Dataset

The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.

It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

The columns in this dataset are:

Id,
SepalLengthCm,
SepalWidthCm,
PetalLengthCm,
PetalWidthCm,
Species.

## Project Structure

The project contains the following files:

- `ML_Challenge.ipynb`: Jupyter Notebook containing the data exploration, preprocessing, model training, and evaluation code.
- `Iris.csv`: The data set used for this project.
- `model.pkl`: SVC model which is trained on the data set. 
- `README.md`: This file, providing an overview of the project.

## Dependencies

The project requires the following dependencies to be installed:

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- seaborn
- matplotlib


## Usage

To run the project, open the `iris_classification.ipynb` notebook in Jupyter Notebook and execute the cells sequentially. The notebook contains detailed explanations and comments to guide you through the project steps.

## Results

The project utilizes several classification models to classify Iris flowers based on their measurements. The following models were evaluated:

- Logistic Regression
- Support Vector Classification
- Decision Tree
- Random Forest

After evaluation, it was found that both Logistic Regression and Support Vector Classification achieved high accuracy, precision, and recall scores. The Decision Tree model showed lower performance, while the Random Forest model achieved perfect scores but may be prone to overfitting.

Based on these results, it is recommended to choose Support Vector Classification for further use in the project, considering specific requirements and constraints.

## Contributions

- Sangem Jaya Prakash:
  - Implemented the data preprocessing steps.
  - Trained and evaluated the Logistic Regression and Support Vector Classification models.
  - Prepared the README file.

- Gundlapalle Yashashree:
  - Implemented the model training and evaluation functions.
  - Trained and evaluated the Decision Tree and Random Forest models.
  - Created visualizations for the evaluation results.

## Conclusion

In this project, we developed a classification model to predict the iris flower species. The Support Vector Classification model achieved the highest accuracy of 0.99, indicating its effectiveness in this classification task. However, further analysis is required to determine the most suitable model for deployment in real-world scenarios.

For any inquiries or collaborations, please feel free to contact:

- Jaya Prakash: 21211a7253@bvrit.ac.in
- Yashashree: 21211a7221@bvrit.ac.in