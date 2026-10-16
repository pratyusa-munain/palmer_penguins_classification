## Palmer Penguins Species Classification 🐧

## Project Overview
This project uses Machine Learning to classify penguin species based on physical measurements. It uses the Palmer Penguins dataset and compares two classification algorithms: K-Nearest Neighbors (KNN) and Decision Tree.

## Dataset
The dataset contains penguin measurements and species labels.
Dataset source: "Palmer Penguins Dataset" (https://allisonhorst.github.io/palmerpenguins/)
----Accessing the dataset requires internet connection btw.

## Technologies Used
- Python
- Jupyter Notebook
----(Imported Libraries)----
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Models and Results
Model| Accuracy
K-Nearest Neighbors (KNN, k=5)| 100%
Decision Tree| 98.55%
----These results are based on the train-test split used in the notebook. Performance may vary with a different split or random state. 

## How to Run
1. Install Python and Jupyter Notebook.
2. Download or clone this repository.
3. Install the required libraries:
   
   pip install pandas numpy matplotlib seaborn scikit-learn

4. Open Jupyter Notebook:
   
   jupyter notebook

5. Open "palmer_penguins_classification.ipynb" and run the cells from top to bottom.

## Conclusion
The project demonstrates how Machine Learning can classify penguin species using physical measurements. KNN achieved the highest accuracy on the current test split, while the Decision Tree model also performed well.