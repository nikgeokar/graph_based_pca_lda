# Graph-Based Pca Lda
Welcome to our repository, where we present a methodology for predicting node labels of graphs using machine learning.

Our approach involves creating a pipeline that utilizes graph-based Kernel Principal Component Analysis (KPCA) for dimensionality reduction, followed by using the transformed dataset to train a Linear Discriminant Analysis (LDA) classifier. We have used multi-output LDA to predict labels for all the nodes in the graph.

In this project, we have performed experiments with two datasets. The first dataset is the parking violation data of Thessaloniki's controlled parking system, where we predict the parking violation rate of sectors. The second dataset is the chickenpox dataset, where we try to predict disease outbreaks. Although these are regression tasks, we converted them into classification problems for comparison with our previous works.

We have also conducted additional experiments for both datasets using common KPCA methods as well as the K-Nearest Neighbor algorithm.

In this repository, you will find all the necessary code, documentation, and datasets used in our project. We have also included a detailed report that outlines our methodology and presents our findings.

Our aim with this project is to showcase the effectiveness of our methodology in predicting node labels of graphs using machine learning. We invite you to explore our repository and see how our pipeline can be applied to other similar problems.

To access further details and information, please refer to the report file located within this repository (report.pdf).
