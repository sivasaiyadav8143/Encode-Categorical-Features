# Encode-Categorical-Features

**Handling Categorical/Qualitative variables** is an important step in data preprocessing.Many Machine learning algorithms can not understand categorical variables by themself unless we convert them to numerical values.
The performance of ML algorithms is based on how Categorical variables are encoded. The results produced by the model varies from different encoding techniques used.

Categorical variables can be divided into two categories:<br>
1. Nominal (No order) 
2. Ordinal (some order).

<img src="Screenshots/Categorical_variables.png">

## There are many ways we can encode these categorical variables ##

1. One Hot Encoding
2. Label Encoding
3. Ordinal Encoding
4. Frequency or Count Encoding
5. Binary Encoding
6. Base-N Encoding
7. Helmert Encoding
8. Mean Encoding or Target Encoding
9. Weight of Evidence Encoding
10. Sum Encoder (Deviation Encoding or Effect Encoding)
11. Leave One Out Encoding
12. CatBoost Encoding
13. James-Stein Encoding
14. M-estimator Encoding
15. Hashing Encoding
16. Backward Difference Encoding
17. Polynomial Encoding
18. MultiLabelBinarizer

# Following libraries are used to perform encoding.
!pip install scikit-learn <br>
!pip install category-encoders <br>

## Below cheat-sheet is a guiding tool to select enconding method. ## 
<br>
<img src="Screenshots/Categorical_Encoding.png">

# References #

1. [Category Encoders Documentation](http://contrib.scikit-learn.org/category_encoders/index.html)
2. https://medium.com/swlh/an-introduction-to-categorical-feature-encoding-in-machine-learning-cd0ca08c8232
3. https://towardsdatascience.com/benchmarking-categorical-encoders-9c322bd77ee8
4. https://towardsdatascience.com/all-about-categorical-variable-encoding-305f3361fd02
5. https://towardsdatascience.com/an-easier-way-to-encode-categorical-features-d840ff6b3900

