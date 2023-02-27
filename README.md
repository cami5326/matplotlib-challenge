# matplotlib-challenge

In this activity, it was requested an analysis of Capomulin, a pharmaceutical company drug, in the treatment of squamous cell carcinoma (SCC) against other treatment regimens.
Here you can find a top-level summary of the study results:

* There were 248 mice participants on the study. 51% were male, 49% were female. 

![sex](https://github.com/githubemail5326/matplotlib-challenge/blob/main/Pymaceuticals/sex.PNG)

* Capomulin had a better performance than most of the treatment regimens, comparing their mean, median, variance, standard deviation and standard error, except for Ramicane. 

![agg](https://github.com/githubemail5326/matplotlib-challenge/blob/main/Pymaceuticals/agg.PNG)


* Capomulin and Ramicane boxplots demonstrate they are better treatments when compared to Infubinol, and Ceftamin: the final tumor volume of the first group was smaller than the second group, despite Infubinol outlier. 

* Comparing Capomulin and Ramicane, we notice similar results regarding the variance of the datasets, but Ramicane has a lower minimum, maximum and median final tumor volume values. Ramicane has a larger interquartile (spread of the middle 50% of the data), though. 

![boxplot](https://github.com/githubemail5326/matplotlib-challenge/blob/main/Pymaceuticals/boxplot.PNG)

* There is a strong correlation between the mouse weight and the average tumor volume for Capomulin: the Pearson correlation coefficient is 0.84, indicating the weight of the patient may play an important role when they are being treated with Capomulin. More data is needed to obtain a conclusive analysis.

![correlation](https://github.com/githubemail5326/matplotlib-challenge/blob/main/Pymaceuticals/correlation.PNG)

—