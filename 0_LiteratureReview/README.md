# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Flying Insect Classification with Inexpensive Sensors

  - **https://link.springer.com/article/10.1007/s10905-014-9454-4**
  - **Objective**: automatically classify insects based on sound like data 
  - **Methods**: Bayesian classifier
  - **Outcomes**: 79.44% accuracy for 10 classes
  - **Relation to the Project**: original paper on this classification problem, authors are the source of the dataset used in this project

- **Source 2**: An introduction to Dynamic Time Warping

  - **https://rtavenar.github.io/blog/dtw.html**
  - **Objective**: The article explains how Dynamic Time Warping can overcome the shortcomings, many similarity metrics have for time series. Especially time series that have very similar patterns which are only offset from each other, are often regarded as not very similar.
  - **Methods**: In contrast to many other similatity metrics, Dynamic Time Warping does not calculate the difference of the values of the two time series at the same time stamp. Instead, it tries to align the time series in a way to minimize the difference between all data points by aligning them in a different way. Therefore, some of the data points can be multiplicated.
  - **Outcomes**: Dynamic Time Warping can identify similarities between time series better, especially when they have a temporal offset to each other.
  - **Relation to the Project**: We used Dynamic Time Warping as similarity measure in the clustering process for the analysis of the Insect Sound dataset. 

  
