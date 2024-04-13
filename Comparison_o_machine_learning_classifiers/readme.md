# Comparison of Machine Learning Classifiers

This project serves the purpose of evaluating and comparing the performance of various machine learning classifiers using synthetic data generated with `make_classification` from `sklearn.datasets`. The classifiers are assessed based on their accuracy scores utilizing a train-test split methodology.

## Methodology
### Data Generation
Synthetic data comprising 1000 samples, 5 features, and 2 classes is generated using `make_classification`.

### Train-Test Split
The dataset is partitioned into training and testing subsets with an 80-20 ratio using `train_test_split` from `sklearn.model_selection`.

### Classifier Selection
Thirteen distinct classifiers are chosen from the `sklearn` library, covering a broad spectrum of machine learning algorithms, including k-Nearest Neighbors, Support Vector Machines with various kernels, Gaussian Process, Gradient Boosting, Decision Trees, Extra Trees, Random Forest, Neural Network, AdaBoost, Naive Bayes, Quadratic Discriminant Analysis, and Stochastic Gradient Descent.

### Model Training and Evaluation
Each classifier undergoes a training phase using the training data, followed by evaluation based on their accuracy scores computed using the testing data.

### Visualization
The accuracy scores of the classifiers are represented through a horizontal bar plot, facilitating an analysis of their performance.

## Dependencies
- Python 3.x
- scikit-learn
- matplotlib
- pandas