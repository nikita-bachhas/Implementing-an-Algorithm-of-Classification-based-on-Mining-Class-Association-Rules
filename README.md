# Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules
This project implements a classifier and compares it against other classification methods.

## Functionality
1. Preprocessing stage: Identified the mode of the column and filled in missing values
2. Carried out data discretisation, replacement of numerical data with number of intervals-consecutive positive integers and data binning
3. Generation of Mining Class Association rules: The rule generator implemented is similar to the one as the Apriori algorithm 
4. All rules generated satisfy the minimum support and minimum confidence of 0.01 and 0.5 respectively 
5. Classifier: Implemented an improved version of a classifier based on the classifier from the ‘Bing Liu, Wynne Hsu, Yiming Ma: Integrating Classification and Association Rule Mining. KDD 1998: 80-86’ paper
6. Evaluation: Compared against the original classifier from the paper and other classification methods implemented like Decision trees (with pruning and without pruning), Random Forest, SVM and Logistic Regression (liblinear and saga) 

## Documentation 
All documents can be found under the [Documentation](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/tree/main/Documentation) folder
1. Detailed report of the project: [Report.pdf](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Documentation/Report.pdf)
2. Project Video: [CZ4032 Project 1 Video](https://www.canva.com/design/DAEtXU88tU0/rhnEjfku-NV2Q8J_FagjLA/watch?utm_content=DAEtXU88tU0&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton)

## Datasets 
All datasets can be found under the [Datasets](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/tree/main/Datasets) folder
1. [Iris](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/iris.data) and [names](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/iris.names): This dataset contains the petals and sepals size of 3 different species of Iris plants.
2. [Tic-Tac-Toe](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/tic-tac-toe.data) and [names](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/tic-tac-toe.names): This dataset contains a complete set of possible board configurations at the end of tic-tac-toe game, when ‘x’ is assumed to have played 
3. [Zoo](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/zoo.data) and [names](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/zoo.names): This dataset contains information about the animals in the zoo and their corresponding features.
4. [Glass](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/glass.data) and [names](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/glass.names): This dataset contains information about the different types of glasses.
5. [Wine](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/wine.data) and [names](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/wine.names): This dataset contains information about the different types of wines
6. [Teaching Assistant Evaluation (Tae) Date](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/tae.data) and [names](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/tae.names): This dataset contains information about different teacher’s evaluations.
7. [Breast Cancer Coimbra](https://github.com/nikita-bachhas/Implementing-an-Algorithm-of-Classification-based-on-Mining-Class-Association-Rules/blob/main/Datasets/Breast%20Cancer%20Coimbra%20Data%20Set.csv): This dataset contains information about the patients with breast cancer.

## Developed By
1. Ang Shu Hui
2. Bachhas Nikita
3. Srinivas Shruthi
4. Unnikrishnan Malavika
