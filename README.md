# unsupervised-machine-learning-challenge

As a memeber of the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, I have been asked to explore this possibility by using unsupervised learning.

You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

PCA findings:
From PCA analysis, after applying a standard scalar, 92% of the information in the data is represented with 10 components. 4 dimensions were dropped.

t-SNE findings:
After adjusting the learning rate, the t-SNE model does appear to be able to identify two overlapping clusters in the data.

K-Means findings:
From the chart, the recommendation would be there are 8 klusters or groups that the patients can be put in. I have come to this detrmination based on observing the K-Means chart and establishong that the curve starts to flatten at 7. This means there is not much more value in having more than 8 klusters.  

Files 
Myopia.ipynb - Jupyter notebook used to analysis dataset

myopia.csv - dataset used in analysis