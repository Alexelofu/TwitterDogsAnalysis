# TwitterDogsAnalysis

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the 
dog. These ratings almost always have a denominator of 10. The numerators, though? Almost 
always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." 
WeRateDogs has over 4 million followers and has received international media coverage.
Data used in this project was provided by Udacity and as it was a requirement for my data 
analyst nanodegree program. The archive contains basic tweet data (tweet ID, timestamp, text, 
etc.) for all 5000+ of their tweets as they stood on August 1, 2017. The data was cleaned to 
remove redundant data. However, not all of the desired data is present in Udacity's dataset, so I also use the Twitter API to gather additional data.

During the wrangling process, only tweets having ratings and images are used. After the data gathering, data cleaning and overall wrangling process, I went on to focus on answering questions. The following questions, I aimed to answer include:

- What dog breed is the most loved?
- What dog breeds have the highest mean score?
- What source produces the most tweets?
- What dogs are generally the most loved?


## Requirements
- Jupyter Notebook
- Pandas
- Numpy
- Requests
- Tweepy
- json
- Matplotlib
- Twitter API
