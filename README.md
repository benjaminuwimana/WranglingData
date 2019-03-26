## Data Wrangling

This project was completed as part of the course requirements of Udacity's [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) program. It is a project under the 'Data wrangling' lesson.

___

### Description

The project mainly focuses on the classical three steps of data wrangling process, namely: gathering, assessing and cleaning data. A twitter archive file was provided by Udactiy and it contains 2356 users’ tweets each of which having 17 attributes. Other files were required to complete the project and instructions were given on how to gather them from different sources. All of these files are related to tweets from WeRateDogs twitter user account. WeRateDogs rates people's dogs with a humorous comment about the dog.

Steps to complete the project include:
- Data gathering
- Assessing gathered data for quality and tidiness
- Cleaning datasets
- Analyse and visualise three insights
___

### Tools used to complete the project

- Python, Numpy, Pandas, Matplotlib, sqlalchemy, Image from IPython.display
- Jupyter Notebook

___

### Conclusion

Important findings are:
- It looks like most of tweets (93%) are of 'Twitter for iPhone' source. Also the above plot shows that most of tweets are made during night hours. It is noticeable that from 6 to 12 hours in the morning there are almost not tweets written. This suggests that maybe most of users are at respective work places and have not time to tweet in the morning and the afternoon.
- The first, second and third algorithms correctely predicted almost equal number of dog images (1477, 1495 and 1446 images respectively). But when comparing their respective performance in terms of confidence level, we see that the first algorithm is doing better than the other two.
The distribution confidence level for first algorithm varies much more than the distribution for the two other algorithms. There's a significant difference in the median confidence level for first algorithm form the two other algorithms.
- From the previous few cells, we notice that golden_retriever is the MOST favored breed of dogs in the dataset and japanese_spaniel is the LEAST favored breed.
However the INDIVIDUAL MOST favored dog is of Lakeland_terrier breed while the INDIVIDUAL LEAST favored dog is of English_setter breed.

