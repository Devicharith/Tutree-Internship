Que1) Explain dimension reduction in machine learning?

Ans) In machine learning dimension refer to the number of independent features in the datasets.

     Curse of Dimensionality
     Performance of a model depends on the features as the features increases the Performance of the model increases
     at some point increases in features reduces the Performance of the model.


     So Dimensionality reduction is a technique that reduces the amount data without losing information
     and further eliminating the curse of dimensionality.

     There are few important techniques in dimensionality reduction
       1) principal component Analysis (PCA)
       2) Linear Discriminant Analysis (LDA)

     principal component Analysis(PCA)

     Its is one of the popular methods used for dimensionality reduction
     To under stand PCA better we need to get our hands dirty
     lets understand what pca does in background

     Steps:
     1> Given N data vectors from n-dimensions, find p ≤ n orthogonal vectors (principal components) that can be best used to    represent data.

     2> Normalize input data: Each attribute falls within the same range.

     3> Compute k orthonormal (unit) vectors
     To find the vectors we take the dataset.
     Then find the correlation matrix which is going to be symmetrical matrix

     now we compute eigen values then compute eigen vectors using the eigen values.

     The link below will give you a good idea about the correlation matrix(heat map) and eigen values and vectors.
     https://www.itl.nist.gov/div898/handbook/pmc/section5/pmc552.htm

     4>The principal components are sorted in order of decreasing “significance” or strength.

     5>Since the components are sorted, the size of the data can be reduced by eliminating the weak components, i.e., those with low variance.

     Advantages:
     1>Removes the features the has less importance.
     2>Improves the computation speed and Performance of the model.
