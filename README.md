# Iris KNN Classifier

A Jupyter notebook that classifies iris flowers as *setosa*, *versicolor* or *virginica* from their measurements, using a K-nearest neighbours (KNN) model in scikit-learn.

## Results

The model reached **97% accuracy** on the held-out test set (38 samples).

## What the notebook covers

1. Loading the Iris dataset from scikit-learn and inspecting its structure
2. Splitting the data into training and test sets (`random_state=0` for repeatability)
3. Exploring the data with a pandas scatter matrix, coloured by species
4. Training a KNN classifier (`n_neighbors=1`)
5. Predicting the species of a new, unseen flower
6. Evaluating the model on the test set

## Tech Stack

- Python
- scikit-learn
- pandas and NumPy
- matplotlib and mglearn
- Jupyter Notebook

## Getting Started

```bash
git clone https://github.com/<your-username>/iris-knn-classifier.git
cd iris-knn-classifier
pip install -r requirements.txt
jupyter notebook IrisML.ipynb
```

## Project Structure

```
iris-knn-classifier/
├── IrisML.ipynb        # Main notebook
├── requirements.txt    # Dependencies
└── README.md
```

## Possible Improvements

- Compare different values of `k` and plot accuracy against `k`
- Use cross-validation instead of a single train/test split
- Add a confusion matrix to show which species get confused
- Compare KNN against other classifiers (decision tree, logistic regression)

## Acknowledgements

Based on exercises from *Introduction to Machine Learning with Python* by Andreas Müller and Sarah Guido.

## Author

Aimee Teppo
