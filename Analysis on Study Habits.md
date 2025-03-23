# Clustering Analysis on Study Habits

## Executive Summary
This study explores time management and gender-related differences among 500 12th grade students in the US, more specifically exploring time spent on doing homework and watching TV. All analyses were performed using JMP software. Employing K-Means clustering analysis, three distinct clusters were identified: cluster 1, consisting of substantial hours spent on homework and few hours watching TV; cluster 2, consisting of moderate time spent on homework and substantial time spent on watching TV; and cluster 3, with few hours doing homework and few hours watching TV. Furthermore, while contingency analysis resulted in a statistically significant distribution of gender across the clusters, regression analysis through fit least squares revealed that gender does not significantly affect the pattern allocation of time to different activities. These findings suggest that gender is not a driver of time management habits, but rather behavioral differences are. Thus, policies and initiatives should not be gender-based but rather target behavioral patterns, which could be further explored through future surveys that include questions exploring different variables for a deeper comprehension of the diverging patterns revealed.  

## Background
Time management is a highly important factor that influences academic performance in high school students. Understanding how different factors affect this behavior, such as gender differences, may reflect broader trends in how individuals allocate their time and in school social dynamics. Through the examination of gender-based differences in time spent in doing homework and in watching TV, this analysis aims to bring to light potential differences that could influence academic results.
This study utilizes a sample collected in 2013 of 500 12th grade students from the United States, with the variables state, region, and survey responses. Cluster analysis is applied to explore overall differences and gender differences in average time spent on homework and watching TV, seeking to group students into clusters of similar habits and showcasing how time management may differ across genders. All the analyses conducted was performed in the JMP software.

## Problem
Are there differences in students’ average time spent doing homework and watching TV and can distinct patterns and gender-based variances be found in how time is allocated?

## Analysis
To conduct an analysis on the time allocation between hours spent on homework and hours watching TV, cluster analysis was initially performed to group data points that indicated similar behavior amongst groups of students. K-Means clustering was selected in this case as it is suitable for slightly larger data sets as well as those presenting continuous variables (in this case, hours reported watching TV or doing homework). In order to select the optimal number of clusters, different CCC values, which determine the quality of separation between the resulting clusters, were analyzed through K-Means. In this case, the optimal CCC value of -3.0632 was a result of a three-cluster separation. The results of this clustering analysis are observed in Figure 1, which displays the scatterplot of data points grouped into the three diverging clusters. The red circle corresponds to cluster 1, green to cluster 2, and blue to cluster 3.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b456cd6a-d604-43c2-9269-59d320507a68" width="300"/>
</p>  
<div align="center">
<i> Figure 1: K-Means scatterplot of hours spent doing homework by hours spent watching TV </i> 
</div>
<br>

By observing Table 1 below, one may also classify different behaviors amongst the students grouped in each of the clusters. Cluster 1 englobes students with high number of hours on homework, and low number of hours watching TV. Cluster 2 presents moderate hours on homework and high hours watching TV. Lastly, cluster 3 presents low number of hours on homework as well as watching TV.

<p align="center">
  <img src="https://github.com/user-attachments/assets/417f8931-69d3-46b6-894f-b4a38e8f9fe1" width="300"/>
</p>  
<div align="center">
<i> Table 1: Cluster means values for each resulting cluster </i> 
</div>
<br>

The three divergent resulting clusters indicate that students do not allocate equal hours on homework and watching TV and that there are different behavioral patterns in the data. To further investigate and comprehend the effects of gender in these behaviors, Contingency Analysis was performed.  
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/3f9cceab-dc54-4450-94e3-b2b1c15b76d4" width="300"/>
</p>  
<div align="center">
<i> Figure 2: Mosaic plot resulting from contingency analysis of gender by cluster </i>
</div>
<br>

The proportion of males and females in each of the three clusters is displayed the mosaic plot in Figure 2. Additionally, through a Chi-Square test, the relationship was statistically examined, yielding a p-value (Prob>ChiSq) of 0.0448, displaying a statistically significant difference between the distribution of males and females across the clusters. However, to then comprehend the combined effects of gender and cluster membership, a regression analysis through the Fit Least Squares technique was conducted.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/5ef6c9da-1965-482e-9445-cc6b9a4ab75d" width="300"/>
</p> 
<div align="center">
<i> Figure 3: Leverage plot of Gender*Cluster regression through Fit Least Squares </i>
</div>  
<br>

The analysis of the interaction between gender and cluster yielded a p-value of 0.4933. This non- significant result suggests that gender differences within the clusters appear to be consistent. Further regressions were conducted plotting hours spent on homework by hours watching TV (p-value of <.0001), hours spent on homework by gender (p-value of 0.4667), and hours spent on homework by clusters (p-value of <.0001). These results indicate that the differences within clusters are only significantly significant when explained by behavioral differences, but not by gender. Thus, it can be concluded that the gender differences in average responses about hours spent on homework and on watching TV are not significant and that the habits of respondents remain consistent across all clusters regardless of gender and are explained instead by their behavior.


## Conclusions and Recommendations
This analysis identified three different groups within the student respondents: those who spend a substantial time on homework hours and low hours on watching TV; those who spend moderate time on doing homework and a significant time watching TV; and those who spend little time both on doing homework and on watching TV. These differences could be further explored by expanding the diversity of questions surveyed in order to comprehend where the differences in time management stems from for each cluster identified.
Moreover, while a statistically significant relationship between gender and belonging to a specific cluster was identified, gender differences for each cluster were found to not be statistically significant through regression. This result indicated that while gender might be relevant, it is not what drives the behavioral differences in the observed clusters. These findings indicate that if time management initiatives were to be implemented based on these results, they should not focus on gender-specific strategies, but rather, should focus on the behavioral differences themselves. As discussed, further drivers of these divergences could be identified by conducting future surveys that explore other possible factors that might influence clustering of these variables.
The division of this data in divergent clusters might assist dietary initiatives among students with different nutritional habits. Educational initiatives that promote balanced nutrition would greatly benefit from understanding the number of students belonging to each cluster and how that could shape programs targeted at improving nutrition amongst the students. Other surveys could in the future be conducted to better understand the causes of these differences in dietary habits.
