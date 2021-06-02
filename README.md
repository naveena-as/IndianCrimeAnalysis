# IndianCrimeAnalysis
Indian Crime Analysis over the period 2001-2012 using Data Visualisation in Python

### About the project
The aim of this project is to visualise the various trends in crimes committed in India (2001-2012), using various Python packages. 20 questions are framed for which answers are obtained using inferences from the corresponding visualisation charts.

### Dataset
The dataset used here is [crimes.csv](https://www.kaggle.com/shishir349/indian-crime-analysis?select=crimes.csv), collected from Kaggle. The same has been uploaded [here](https://raw.githubusercontent.com/naveena-as/IndianCrimeAnalysis/main/crimes.csv) for easy download. It consists of the details of crimes committed in all states and union territories of India every year from 2001-2012. The details include the type of crime and number of people involved in the crime, differentiated into columns based on their gender and age group. For each state/UT, at the end of all the 12 years' data (rows), there is a separate row with purpose as "total", which gives the column wise cumulative sum of the count of people involved in crimes in that state.

### Visualisation
The packages used here are [pandas](https://pypi.org/project/pandas/), [numpy](https://pypi.org/project/numpy/), [seaborn](https://pypi.org/project/seaborn/), [plotly](https://pypi.org/project/plotly/), [matplotlib](https://pypi.org/project/matplotlib/), [wordcloud](https://pypi.org/project/wordcloud/). Various univariate/ bivariate/ multivariate visualisation techniques like bar graph and its variants, line graph, pie chart, donut chart, stacked line plot, scatter plot, scatter matrix, boxplot, violin plot, treemap, parallel plot and wordcloud has been used for drawing conclusions.

Refer to the [report](https://github.com/naveena-as/IndianCrimeAnalysis/blob/main/report.pdf) for further details about the dataset, questions framed, and inferences.

_NOTE : The interactive plots generated with plotly are not visible in the Python notebook preview. However, running the code will generate the desired output. See the images in [output](https://github.com/naveena-as/IndianCrimeAnalysis/tree/main/output) directory for reference._
