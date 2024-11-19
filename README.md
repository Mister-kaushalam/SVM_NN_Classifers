# Support Vector Machine and Neural Network Classifiers

In one of the previous projects; ["Model_Complexity_and_Regularization_Study"](https://github.com/Mister-kaushalam/Model_Complexity_and_Regularization_Study), we looked at casting our datasets into higher dimensions to increase their linear separability and thus make the job for our learning algorithms (finding a boundary between the classes or fitting a function to the points) easier. We  then saw how we can add very high orders of (combinations) of features and use regularization and/or cross-validation to manage the complexity of our final model and thus obtain good out-of-sample performance.

In this project, we will look at a classifier that does both by design: the Support Vector Machine or SVM. The SVM algorithm was developed by Vladimir Vapnik and popularised in the 1990's and is still a popular algorithm. We will also take a closer look at neural networks which are also able to perform non-linear transforms on the input features through the use of non-linear activation functions. 

We'll see how SVMs can take data transformations to the extreme and can perform a transformation to an infinite dimensional space! We will use SVMs on a few different artifical data sets to explore how to manipulate the hyper parameters to get the best results and to build our understanding of how an SVM does its job.

We'll explore neural networks, their structure and the various hyper-parameters associated with neural networks. We'll train neural networks on the same datasets and compare their performance with that of the SVMs.

This project demonstrates the application of **Support Vector Machines (SVM)** and **Neural Networks (NN)** for classification tasks across various datasets. The primary goal is to explore hyperparameter tuning, kernel selection, and optimization techniques, providing insights into the mechanisms and capabilities of these machine learning algorithms.

---

## Overview

### Objective
1. **SVM Exploration:**
   - Investigate how SVMs use kernels to separate data, even in non-linear scenarios.
   - Explore the impact of the **C-parameter** in managing hard and soft margins for optimal classification.
   - Examine kernel transformations, including infinite-dimensional spaces, for non-linear data.

2. **Neural Network Exploration:**
   - Understand the structure and hyperparameters of Neural Networks.
   - Use **Bayesian Optimization** to efficiently search for the best hyperparameter configurations.
   - Compare the performance of SVMs and Neural Networks across multiple datasets.

3. Highlight the importance of:
   - Regularization and cross-validation to manage model complexity.
   - Kernel selection and hyperparameter tuning for improving model generalization.

---

## Datasets

- **Dataset 1:** Linearly separable data used to demonstrate SVM margins (hard vs. soft).
- **Datasets 2 & 3:** Non-linear datasets requiring kernel transformations and complex hyperparameter tuning.
- Train and test datasets were used to evaluate out-of-sample performance.

---

**Libraries:**
  - **NumPy**: Numerical computations
  - **Matplotlib**: Data visualization
  - **scikit-learn**: Machine learning models
  - **scikit-optimize**: Bayesian optimization for hyperparameter tuning

---

## Methodology

1. **Linear SVM for Dataset 1:**
   - Implemented SVM with a linear kernel.
   - Explored the impact of the C-parameter on hard and soft margins.

2. **Kernel Exploration for Non-Linear Data (Datasets 2 & 3):**
   - Experimented with different kernels (e.g., RBF, polynomial).
   - Conducted hyperparameter tuning to improve classification accuracy.

3. **Neural Network Classifier:**
   - Designed and trained neural networks with various architectures.
   - Used Bayesian optimization to efficiently explore large hyperparameter spaces.

4. **Model Comparison:**
   - Compared SVMs and Neural Networks on datasets 2 and 3.
   - Evaluated strengths and limitations of both approaches.

---

## Results

- Demonstrated how **SVMs** leverage kernel functions to classify non-linear data effectively.
- Showcased the role of the **C-parameter** in balancing margin width and misclassification trade-offs.
- Highlighted the importance of **Bayesian Optimization** in reducing the computational cost of hyperparameter tuning for neural networks.
- Provided insights into the complementary strengths of SVMs and Neural Networks.

---

## Project Structure

```
Project_SVM_NN/
│
├── SVM_NN_Classifiers.ipynb   # Main notebook with SVM and NN implementations
├── dataset_1_train.csv    # Dataset for linear SVM experiments
├── dataset_2_train.csv    # Non-linear dataset
├── dataset_2_test.csv     # Test set for dataset 2
├── dataset_3_train.csv    # Another non-linear dataset
├── dataset_3_test.csv     # Test set for dataset 3
│
├── README.md              # Project documentation
```

---

## How to Run the Project

1. Install the required dependencies. Instructions as a code block in the notebook itself.

2. Run the cells sequentially to explore the results.

---

## Future Enhancements

- Apply the models to real-world datasets.
- Experiment with additional kernel types and activation functions.
- Integrate advanced optimization techniques for further efficiency.

---

## Author

- **Kaushal Bhavsar**
- **LinkedIn:** [Kaushal Bhavsar](https://www.linkedin.com/in/kb07/)
- **GitHub:** [Mister-kaushalam](https://github.com/Mister-kaushalam)
- **Email:** Kaushalbhavsar0007@gmail.com
