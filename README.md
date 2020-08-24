# Way-to-Encode-Categorical-Features

**Handling Categorical/Qualitative variables** is an important step in data preprocessing.Many Machine learning algorithms can not handle categorical variables by themself unless we convert them to numerical values.
And performance of ML algorithms is based on how Categorical variables are encoded. The results produced by the model varies from different encoding techniques used.

Categorical variables can be divided into two categories:<br>
1. Nominal (No particular order) 
2. Ordinal (some ordered).

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

# We are gonna use following libraries to perform encoding.
!pip install scikit-learn
!pip install category-encoders
