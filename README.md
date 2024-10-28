# Recommender-System-Practical-Data-Science-
This project was deployed as the Assignment 3 of the COSC2670 - Practical Data Science course. It implements and compares different recommendation system approaches using the MovieLens 1M dataset. The implementation includes KNN Collaborative Filtering and Matrix Factorization techniques, with a focus on performance evaluation and comparison.

## Overview

The project consists of three main tasks:
1. KNN-based Collaborative Filtering
2. Matrix Factorization using SVD
3. Ranking-based Evaluation and Comparison

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Surprise
- Matplotlib
- Seaborn

## Install required packages:
```bash
pip install numpy pandas scikit-learn surprise matplotlib seaborn
```
## Dataset: The MovieLens 1M dataset is used, containing:

1,000,209 ratings
6,040 users
3,900 movies
Rating scale: 1-5

## Implementation Details
Task 1: KNN-based Collaborative Filtering

User-based collaborative filtering
Parameters tested:

k values: [5, 10, 20, 50, 100]
Similarity metrics: Cosine Similarity and Pearson Correlation

Evaluation using RMSE

## Task 2: Matrix Factorization

SVD implementation
Model improvements:

Reduced factors (30)
Increased regularization (0.06)
Extended training epochs (30)
Optimal learning rate (0.005)

## Task 3: Ranking-based Evaluation
Train-Test Split: 80%-20%
Metrics: AP and NDCG
Comparison of both approaches

Results
Key findings:

KNN optimal performance: RMSE = 0.8771 (k=100)
SVD improved performance: RMSE from 1.0123 to 0.9971
Ranking evaluation:

KNN: AP=0.8597, NDCG=0.9669
SVD: AP=0.8755, NDCG=0.9746

## References
[1] Dharaneeshwaran, S. Nithya, A. Srinivasan and M. Senthilkumar, "Calculating the user-item similarity using Pearson's and cosine correlation," 2017 International Conference on Trends in 
Electronics and Informatics (ICEI), Tirunelveli, India, 2017, pp. 1000-1004, doi: 10.1109/ICOEI.2017.8300858. 
[2] T. Chai and R. R. Draxler, "Root mean square error (RMSE) or mean absolute error (MAE)? – Arguments against avoiding RMSE in the literature," Geoscientific Model Development, vol. 7, 
pp. 1247–1250, 2014. doi: 10.5194/gmd-7-1247-2014. 
[3] A. Garrod, S. Parr, M. O’Neil, and R. Guarasci, "A digital elevation model (DEM) for hydrological analysis," CiteSeerX, Accessed: Oct. 24, 2024. [Online]. Available: 
https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=18d3b02c75d6e350b497fb8b3a06a9033bbb5c07
[4] Y. Wang and G. Mori, "A Discriminative Latent Model of Object Classes and Attributes," in Proceedings of the 30th International Conference on Machine Learning, Atlanta, GA, USA, 
2013. [Online]. Available: https://proceedings.mlr.press/v30/Wang13.html
[5] C. C. Aggarwal, Recommender Systems: The Textbook. Cham, Switzerland: Springer, 2016, pp. 139-157. doi: 10.1007/978-3-319-29659-3.
[76] F. Ricci, L. Rokach, and B. Shapira, Eds., Recommender Systems Handbook. New York: Springer, 2015. doi: 10.1007/978-1-4899-7637-6.
[7] A. I. Schein, A. Popescul, L. H. Ungar, and D. M. Pennock, "Methods and metrics for cold-start recommendations," in Proceedings of the 25th Annual International ACM SIGIR Conference 
on Research and Development in Information Retrieval, Tampere, Finland, 2002, pp. 253-260. doi: 10.1145/564376.564421.
[8] Y. Koren, R. Bell, and C. Volinsky, "Matrix factorization techniques for recommender systems," Computer, vol. 42, no. 8, pp. 30-37, Aug. 2009. doi: 10.1109/MC.2009.263.
[9] S. Kabbur, X. Ning, and G. Karypis, "FISM: Factored Item Similarity Models for Top-N Recommender Systems," in Proceedings of the 19th ACM SIGKDD International Conference on 
Knowledge Discovery and Data Mining, Chicago, IL, USA, 2013, pp. 659-667. doi: 10.1145/2487575.2487589.
[10] R. Burke, "Hybrid Recommender Systems: Survey and Experiments," User Modeling and User-Adapted Interaction, vol. 12, no. 4, pp. 331-370, Nov. 2002. doi: 
10.1023/A:1021240730564.
[11] G. Linden, B. Smith, and J. York, "Amazon.com recommendations: Item-to-item collaborative filtering," IEEE Internet Computing, vol. 7, no. 1, pp. 76-80, Jan.-Feb. 2003. doi: 
10.1109/MIC.2003.1167344.
[12] L. Candillier, F. Meyer, and M. Boullé, "Comparing state-of-the-art collaborative filtering systems," in Proceedings of the 5th International Conference on Machine Learning and Data 
Mining in Pattern Recognition, Leipzig, Germany, 2007, pp. 548-562. doi: 10.1007/978-3-540-73499-4_42.
[13] Y. Koren, R. Bell, and C. Volinsky, "Matrix factorization techniques for recommender systems," Computer, vol. 42, no. 8, pp. 30-37, Aug. 2009. doi: 10.1109/MC.2009.263.
[14] A. Paterek, "Improving regularized singular value decomposition for collaborative filtering," in Proceedings of KDD Cup and Workshop, 2007, pp. 39-42.
[15] A. Gunawardana and C. Meek, "A unified approach to building hybrid recommender systems," in Proceedings of the Third ACM Conference on Recommender Systems, New 
York, NY, USA, 2009, pp. 117-124. doi: 10.1145/1639714.1639734.



