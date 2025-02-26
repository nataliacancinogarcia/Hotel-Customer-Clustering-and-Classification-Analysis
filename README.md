# Hotel-Customer-Clustering-and-Classification-Analysis
This repository contains a Jupyter Notebook that analyzes hotel customer data using clustering and classification techniques. The goal of this analysis is to segment customers based on their booking behaviors and demographic information, allowing for better marketing strategies and customer management.

## Objectives
* Cluster hotel customers into distinct groups using K-Means and Mean Shift clustering algorithms.
* Classify customers as frequent or occasional visitors based on their number of visits per month.
*	Visualize and evaluate the performance of clustering models using confusion matrices.
*	Train a Decision Tree Classifier to predict customer types based on categorical and numerical features.
*	Assess model performance using accuracy, precision, recall, and F1-score.

## Techniques Used

**1. K-Means Clustering**
*	Principal Component Analysis (PCA) for dimensionality reduction and visualization.
*	K-Means applied to segment customers into clusters.
*	Decision boundary visualization to understand the clustering results.

**2. Evaluation of Clustering**
*	Confusion matrix comparison with ground-truth classification (based on customer visit frequency).
*	Calculation of accuracy, precision, recall, and F1-score for cluster performance evaluation.

**3. Mean Shift Clustering**
*	Automatic estimation of the optimal number of clusters.
*	Visual representation of customer segments.

**4. Decision Tree Classification**
*	Splitting data into training (80%) and testing (20%) subsets.
*	Training a Decision Tree model to classify customers.
*	Visualizing the Decision Tree to interpret decision-making rules.
*	Evaluating model performance with confusion matrix and classification report. 

## Visualizations
*	Cluster decision boundaries for K-Means segmentation.
*	Confusion matrices for clustering and classification evaluation.
*	Decision Tree structure for customer classification.

## Results
*	K-Means clustering showed some alignment with actual customer segments but had false positives in classifying occasional customers as frequent.
*	Mean Shift clustering automatically determined the number of customer segments but had mixed performance in identifying actual frequent visitors.
*	Decision Tree Classification achieved 100% accuracy, correctly classifying customers with no misclassifications in the test set.
 
