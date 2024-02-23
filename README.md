[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/73X8iERu)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=13217431&assignment_repo_type=AssignmentRepo)

The F1-Score is the harmonic mean of precision and recall. This ensures that both false positives (errors in predicting the positive class) and false negatives (errors in predicting the negative class) are taken into account. If we only look at precision or recall separately, we may obtain incomplete information. For example, high accuracy can occur if the model tends to predict the majority as the majority class without considering the minority class.

Relevant for Class Imbalance Cases:
If the class distribution in the dataset is not balanced, the F1-Score provides a more relevant measure of performance than accuracy. This is because accuracy can be misleadingly high if the model tends to predict the majority as the majority class.

Especially for Binary Classification:
The F1-Score is specifically designed for binary classification and provides richer information than metrics that only assess errors in one dimension (e.g., only false positives or false negatives).

Provides Optimal Balance:
By taking the harmonic mean, the F1-Score provides optimal balance between precision and recall. It offers a better overview of how well the model can identify and separate positive and negative classes. Therefore, choosing the F1-Score as an evaluation metric will provide more comprehensive and relevant information, especially in the context of binary classification with an imbalanced class distribution.

Tools: Kaggle, Glob, Matplotlib.pyplot, seaborn, jmd_imagescraper, numpy, random, pandas, PIL.Image, tensorflow, tensorflow.keras.models.Sequential, tensorflow.keras.layers, tensorflow.keras.callbacks, tensorflow.keras.applications, sklearn.metrics.




