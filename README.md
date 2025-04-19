# Muffin vs Cupcake Classification using SVM / Linear Regression

## Project Description

This project involves the use of **Support Vector Machines (SVM)** to classify recipes as either **muffins** or **cupcakes** based on the amount of **flour** and **sugar** used in the recipe. The model is trained on a dataset of muffin and cupcake recipes, with the key ingredients being flour and sugar.

By using a linear kernel in SVM, the project aims to predict whether a given recipe is a muffin or a cupcake based on these two key ingredients.

## Key Features:
- **SVM Classification**: Utilizes Support Vector Machine with a linear kernel to classify between muffins and cupcakes.
- **Data Visualization**: A scatter plot is used to visually analyze the relationship between the two ingredients (flour and sugar) and their corresponding recipe types.
- **Prediction Function**: A function that takes the values of flour and sugar as input and predicts whether the recipe is a muffin or a cupcake.

## Libraries and Tools:
- **Python**: Programming language used for the project.
- **pandas**: Library for data manipulation and analysis.
- **scikit-learn**: Library for machine learning, specifically for building the SVM model.
- **matplotlib & seaborn**: Libraries for data visualization.

## Dataset:
The dataset used for this project is `recipes_muffins_cupcakes.csv`. The dataset contains the following columns:
- **Flour**: The amount of flour used in the recipe (in grams).
- **Sugar**: The amount of sugar used in the recipe (in grams).
- **Type**: The type of recipe, either "Muffin" or "Cupcake".

## How the Model Works:
1. **Data Preprocessing**: The dataset is loaded, and relevant columns (flour and sugar) are extracted. The "Type" column is encoded as 0 for muffins and 1 for cupcakes.
2. **Model Training**: An SVM classifier with a linear kernel is trained on the flour and sugar data, using the encoded recipe type as the target label.
3. **Prediction**: The model can predict the type of a new recipe based on its flour and sugar content.

## How to Run the Project:
1. **Install Required Libraries**:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
