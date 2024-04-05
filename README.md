# Gender Identification using Machine Learning and Pattern Recognition

## Project Overview
This project focuses on a binary classification task using a dataset derived from face images embeddings, aimed at identifying gender. The embeddings consist of 12 continuous observations without physical interpretations, categorized into three age groups without explicit age information. The dataset presents unbalanced classes for both training and evaluation sets.

## Dataset Analysis
- **Training and Evaluation Sets:** The training set includes 720 male and 1680 female samples, while the evaluation set consists of 4200 male and 1800 female samples.
- **Features Analysis:** Features are analyzed for distribution, normalization, and correlation, employing techniques such as Z-normalization and Gaussianization to prepare the data for classification.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) is utilized to reduce dimensionality, preserving most of the dataset's variance.

## Classification Models
A variety of models are evaluated for their effectiveness in gender classification:
- **Gaussian Models:** Multivariate Gaussian (MVG), Naive Bayes, Tied Gaussian.
- **Logistic Regression:** Linear and Quadratic Logistic Regression.
- **Support Vector Machine (SVM):** Linear SVM, Polynomial Kernel SVM, and Radial Basis Function (RBF) SVM.
- **Gaussian Mixture Models (GMM):** Evaluating different components and covariance types.

## Experimental Results
The models are trained and evaluated using K-Fold cross-validation to select the most promising ones based on their performance, particularly focusing on normalized minimum detection costs (minDCF). Score calibration is performed to refine the models' accuracy further. The best-performing model is identified through comprehensive analysis.

## Conclusions
The project demonstrates the efficacy of various machine learning models in gender identification, with specific models showing superior performance in terms of prediction accuracy and computational efficiency. The findings underscore the importance of preprocessing, model selection, and calibration in developing effective pattern recognition systems.

## Authors
- Antonio Ferrigno [s316467]
- Simone Varriale [s315962]

## Acknowledgements
This project was conducted as part of the MLPR Exam at Politecnico of Turin, under the guidance of Sandro Cumani. We extend our gratitude to all contributors and participants for their valuable input and support throughout this project.
