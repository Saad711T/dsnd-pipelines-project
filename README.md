# Reviews of Clothing Analytics and Pipeline

This project represents a ML pipeline for predicting customer recommendation of clothing products. It was written in Jupyter Notebook. This pipeline dealing with many types of data, like (text,numbers,etc.)

## Getting Started

Instructions for how to get a copy of the project running on your local machine.
`git clone https://github.com/Saad711T/dsnd-pipelines-project`

### Dependencies

```
- numpy
- pandas
- scikit-learn
- matplotlib
- scipy
```

### Installation

Run this command in your terminal.
`pip install numpy pandas spacy scikit-learn matplotlib`

## How to use ?

- Open a Jupyter Notebook file.
- Execute the notebook cells.
- Load and explore the dataset.
- Preprocess the data for readiness.
- Construct and train the model within a pipeline.
- Enhance the model using RandomizedSearchCV.
- Assess the final model using the test data.

## Features
### Data Ingestion & Preliminary Analysis
- **Imports the dataset** from a CSV file.
- **Conducts exploratory data analysis** to examine the distribution of data, identify missing values, and evaluate class imbalances.

### Preprocessing & Feature Construction
- **Employs a custom spaCy-based transformer** for text data preprocessing, focusing on lemmatization and removing stopwords.
- **Constructs separate pipelines** for numerical, categorical, and text data using scikit-learn's Pipeline and ColumnTransformer frameworks.

### Model Development & Optimization
- **Embeds a RandomForestClassifier** in a comprehensive pipeline.
- **Utilizes GridSearchCV** for meticulous hyperparameter tuning to enhance model efficacy.

### Visualization & Model Assessment
- **Produces detailed visualizations**, such as plots for feature distribution, class imbalances, and confusion matrices.
- **Generates Word Clouds** to depict prominent terms in review texts.
- **Delivers exhaustive classification reports** and evaluates the model based on accuracy metrics.


This section should contain all the student deliverables for this project.

## Built With

* [Python](https://www.python.org) - Python is High-level language used mainly in machine learning ,data science ,video games ,and back-end web development.
* [Jupyter Notebook](https://jupyter.org) - Jupyter is IDE/Environment using for (Julia & R & Python) with Markdown comments , It's very good tool for ML & Data science.
* [Pandas](https://pandas.pydata.org) - Pandas is python library using for Data manipulation.
* [Numpy](https://numpy.org) - Numpy is python library using for numerical things , and Numpy meaning is "Numerical Python".
* [Scikit-Learn](https://scikit-learn.org/stable) - Scikit-Learn is python library using primarily for ML/DL.
* [Matplotlib](https://matplotlib.org) - Matplotlib is python library using in Data visualization , It's very helpful for Data scientists/analysts.

Include all items used to build project.

## License

[License](LICENSE.txt)
