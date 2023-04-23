# Cosine Similarity Calculations

Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them. Similarity measures have a multiude of uses in machine learning projects. They come in handy when matching strings, measuring distance, and extracting features. This similarity measurement is particularly concerned with orientation, rather than magnitude. In this case study, I will use the cosine similarity to compare both a numeric data within a plane and a text dataset for string matching.

## 1. Cosine Similarity with clusters and numeric matrices

All points in our dataset can be thought of as feature vectors. We illustrate it here as we display the Cosine Similarity between each feature vector in the YZ plane and the [5, 5] vector we chose as reference.

A. Using the 2D matrix and the reference plane of (5,5) we can use a scatter plot to view the way the similarity is calculated using the Cosine angle.

![image](https://user-images.githubusercontent.com/86930309/227801052-32823007-010e-4ace-8b22-3caa074d52cd.png)

B. This is the 3D matrix with the similarity and the reference plane, (5,5,5).

![image](https://user-images.githubusercontent.com/86930309/227801418-2531d372-560b-4670-911e-34e1141b853f.png)

## 2. Cosine Similarity with text data

This is a quick example of how you can use Cosine Similarity to compare different text values or names for record matching or other natural language proecessing needs. First, we use count vectorizer to create a vector for each unique word in our Document 0 and Document 1.

A.

Document1 = "Starbucks Coffee"

Document2 = "Essence of Coffee"

Here, we finally apply the Cosine Similarity measure to calculate how similar Document 0 is compared to any other document in the corpus. Therefore, the first value of 1 is showing that the Document 0 is 100% similar to Document 0 and 0.26055576 is the similarity measure between Document 0 and Document 1.

B.

Document0 = 'tim tebow was a great quarterback'

Document1= 'tebow scored many touchdowns'

0.12735953 Is the similarity measure between the two documents.

