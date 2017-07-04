# K Nearest Neighbors algorithm on Breat Cancer Data

Data Source: [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29)

data set description

```
    Attribute                     Domain
   -- -----------------------------------------
   1. Sample code number            id number
   2. Clump Thickness               1 - 10
   3. Uniformity of Cell Size       1 - 10
   4. Uniformity of Cell Shape      1 - 10
   5. Marginal Adhesion             1 - 10
   6. Single Epithelial Cell Size   1 - 10
   7. Bare Nuclei                   1 - 10
   8. Bland Chromatin               1 - 10
   9. Normal Nucleoli               1 - 10
  10. Mitoses                       1 - 10
  11. Class:                        (2 for benign, 4 for malignant)
  ```

**Notebooks:**

* `knn_with_sklearn.ipynb` - knn using scikit-learn on breast cancer to data to classify if the cancer is benign or malignant
* `knn_custom_implementation.ipynb` - knn algorithm implemented without using any ML library.
* `breast_cancer_data_with_our_knn.ipynb` - custom knn algo acccuracy check on the same breast cancer data.


The idea of using custom knn implemenation is not improve the speed of the algorithm but to see if we can achieve the same accuracy with our own knn algorithm.