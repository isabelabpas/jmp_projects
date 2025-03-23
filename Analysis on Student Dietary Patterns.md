# Analysis on Student Dietary Patterns

## Executive Summary
This study analyzes the dietary patterns of 150 students based on their average daily intake of protein, fat and carbohydrates utilizing the JMP software. The dataset is analyzed employing Hierarchical Cluster analysis, identifying three different clusters of diverging dietary patterns: cluster 1 characterized by moderate protein intake, high fat intake, and moderate carbohydrate intake; cluster 2 characterized by low protein intake, high fat intake, and high carbohydrate intake; and cluster 3 characterized by high protein intake, low fat intake, and low carbohydrate intake. These differences were found to be statistically significant across the clusters through ANOVA and post hoc tests. The findings can inform educational initiatives targeted towards improving nutrition and eating habits addressing specific needs of different student groups. Further research could be conducted to explore the variables influencing differences across clusters to improve nutritional strategies further.

## Background
Dietary habits among students may not only impact their health directly but also influence their performance in a demanding environment. Varied macronutrients pay different roles in making a diet adequate for students, and identifying trends in common dietary patterns can provide helpful insights in consumption trends and highlight areas of improvement. In this study, data was sourced for the average daily consumption of protein, fat, and carbohydrates in grams among 150 students.
This data may be properly assessed through cluster analysis, a method which can be applied to group data points with similar characteristics – in this case, students with similar dietary habits, allowing us to identify patterns in the multivariate data. Through exploring these clusters, dietary profiles from the sample can be uncovered, with quantifiable differences that allow for evaluation of the average daily consumption of macronutrients among students. All of the analyses in this study were conducted utilizing the JMP software and its tools.

## Problem
Can distinct dietary patterns among the students sampled be spotted through clustering analysis of average daily consumption data on protein, fat, and carbohydrates?

## Analysis
In order to analyze dietary patterns based on the consumption of protein, fat, and carbohydrates, cluster analysis was utilized to group data points with similar profiles in nutritional content. Among clustering techniques, Hierarchical Clustering was used because the data set is relatively small, and the technique is suitable for continuous variables such as those provided. Hierarchical Clustering also does not require the establishment of a predefined number of clusters making it a flexible technique to be employed in this case. The results of Hierarchical Clustering are displayed in a dendrogram in Figure 1, providing a comprehensive visualization of groupings in the data and displaying observations based on their similarity with no need for an assumption on cluster quantities.
The performance of the Hierarchical Clustering model was evaluated using the Cubic Clustering Criterion (CCC), which helps in assessing the quality of solutions provided by the technique by measuring the separation between clusters. The CCC that resulted in the highest CCC value for this study and thus optimal solution was achieved by dividing the data into three clusters (CCC = 10.049). This result aligned with the grouping suggested by the dendrogram, confirming that the resulting clusters provided the best way to segment the data in this case. The optimal solution identified consisted of separating the macronutrient consumption patterns into 3 different clusters, showcasing that there are 3 different dietary patterns resulting from the sample, visualized through the dendrogram in Figure 1 and the constellation plot in Figure 2.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/afa96025-17c5-4927-85bc-d78e7ad30830" width="300"/>
</p>  
<div align="center">
<i> Figure 1: Dendrogram resulting from Hierarchical Clustering analysis </i> 
</div>
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3d145425-c23d-4d4a-b109-3486c0129624" width="300"/>
</p>  
<div align="center">
<i> Figure 2: Constellation plot from Hierarchical Clustering analysis </i> 
</div>
<br>

The resulting cluster means which showcase the mean values for each variable in each cluster can be found in Table 1 below:  
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/0e447d60-d989-437f-a0c8-bfd0305d19c2" width="300"/>
</p>  
<div align="center">
<i> Table 1: Cluster means values for each resulting cluster </i>
</div>
<br>

From the values of the cluster means, one can identify three distinct dietary patterns. Cluster 1 consists of a diet characterized of medium protein intake, high fat intake, and medium carbohydrate intake. Cluster 2 consists of low protein intake, high fat intake, and high carbohydrate intake. Cluster 3 consists of high protein intake, low fat intake, and low carbohydrate intake. The cluster means have been graphed below on Figure 3 for ease of visualization of each distinct characteristic between the three resulting clusters.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/2a65e797-20a7-41e1-afcd-4ecfeb190070" width="300"/>
</p> 
<div align="center">
<i> Figure 3: Graph of cluster means of protein, fat, and carbohydrates by cluster </i>
</div>  
<br>

The identification of three different clusters with diverging characteristics indicates that the average daily consumption of protein, fat, and carbs is not uniform across all study participants. To further explore whether there are statistically significant differences among diets, an ANOVA and post hoc tests were performed on the data set through Oneway analysis of the different variables (protein, fat, and carbohydrates) by the cluster. These tests all yielded p-values of <.0001, meaning that there are, in fact, statistically significant differences among diets.


## Conclusions and Recommendations
The analysis performed yielded three different clusters that represent different dietary patterns characterized by different consumption of protein, fat, and carbohydrates. Cluster 1 consists of a moderate intake of protein, high intake of fat, and moderate intake of carbohydrates; cluster 2 presents a low protein intake, a high fat intake, and a high carbohydrate intake; lastly, cluster 3 consists of high protein intake, low fat intake, and low carbohydrate intake. Further analysis confirmed there is, in fact, a statistically significant difference between the clusters’ macronutrients consumption.
The division of this data in divergent clusters might assist dietary initiatives among students with different nutritional habits. Educational initiatives that promote balanced nutrition would greatly benefit from understanding the number of students belonging to each cluster and how that could shape programs targeted at improving nutrition amongst the students. Other surveys could in the future be conducted to better understand the causes of these differences in dietary habits.
