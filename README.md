# Wikipedia-BigdataAnalysis-Project

This analysis consists of using big data tools to answer questions about datasets from Wikipedia. There are a series of analysis questions, answered using Hive and MapReduce. The tools used are determined based on the context for each question. The output of the analysis includes MapReduce jarfiles and .hql files so that the analysis is a repeatable process that works on a larger dataset, not just an ad hoc calculation.

# Technologies Used

1. HDFS
2. HADOOP
3. MAP REDUCE
4. HIVE
5. YARN
6. Git + Github

# Features
1. Find, organize, and format pageviews on any given day.
2. Follow clickstreams to find relative frequencies of different pages.
3. Determine relative popularity of page access methods.

# problem statement

- Which English wikipedia article got the most traffic on January 20, 2021?
- What English wikipedia article has the largest fraction of its readers follow an internal link to another wikipedia article?
- What series of wikipedia articles, starting with Hotel California, keeps the largest fraction of its readers clicking on internal links.

# Data taken from

1. Pageviews March 1st data https://wikitech.wikimedia.org/wiki/Analytics/Data_Lake/Traffic/Pageviews 
2. Monthly Clickstream https://meta.wikimedia.org/wiki/Research:Wikipedia_clickstream
