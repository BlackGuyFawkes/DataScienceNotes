# MY DATA ANALYTICS NOTES

# INTRODUCTION
> This is a repository for my data analytics notes from my udacity Data Analytics Certification Program. It contains the notebooks and summaries of different datasets I worked on.
> There are 3 projects in all. Each project has a summary and a notebook. The summary includes a brief introduction of the dataset, the purpose of the analysis, the findings of the analysis and links for the location on kaggle.com, Github and my portfolio website. 

Enjoy.

# 1. Wrangling and Analyze Data (Udacity Submission)

## Dataset

> Here we have 3 different datasets which with different pieces of infomation. The dataset consists of information regarding individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There were 183412 entries in this dataset with 16 features. Irrelevant features were dropped to make it 6 features (duration_sec, user_type, member_birth_year, member_gender and AgeGroup). There are two numerical columns and three categorical columns. The AgeGroup column was created to classify the member_birth_year into 5 different categories. very old, Old, midlife, young and very young. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

> In the exploration, I discovered that majority of the users of the rideshare are in the midlife and old ages. There is a moderate amount of users who are young with very little amount of them very young and very old. As for their genders, most of the users are male with less than half of them females and very little amount of them with undisclosed genders. A significantly major part of the users are subscribers with very little amount of them falling into the customer category. I also found that there is a correlation between the time spent on the rideshare and agegroup and that users in the midlife and the old group of the age group spent more time user the ride share than any of the other age groups.



![Wrangling Dataset](/wrangling.png)


Kaggle file is [here](https://www.kaggle.com/code/akachimaduako/wrangling-and-analyzing-data-by-maduako-akachi), Notebook can also be found on GitHub [here](https://github.com/BlackGuyFawkes/DataScienceNotes/blob/main/wrangling-and-analyzing-data-by-maduako-akachi.ipynb). A summary can also be found on my portfolio website [here](https://www.maduakoakachi.com/portfolio#h.ejctx7z34vzf)



# 2. TMDB Movie Data Analysis (Udacity Submission)

## Dataset

> The dataset consists of contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. There were 10866 entries in this dataset with 21 features. Irrelevant features ('imdb_id', 'homepage', 'tagline', 'overview', 'production_companies', 'keywords') were dropped to make it 15 features. There are 6 numerical columns and 9 categorical columns. The Genre column was split to give individual genre values. The dataset can be found [here](https://www.kaggle.com/datasets/afsarjan23/tmdb-movies-dataset)


## Summary of Findings

> In the exploration, I discovered that Action, Adventure, Science Fiction, Thriller are the most popular movie genres. I also discovered, by plotting several scatter plots how much revenue was produced over the years.


![Tmdb Dataset](/tmdb.png)

Kaggle file is [here](https://www.kaggle.com/code/akachimaduako/tmdb-movie-data-analysis), Notebook on Github can be found [here](https://github.com/BlackGuyFawkes/DataScienceNotes/blob/main/tmdb-movie-data-analysis.ipynb). A summary can also be found on my portfolio website [here](https://www.maduakoakachi.com/portfolio#h.ux4nd0ef92ys)


# 3. Ford GoBike System Data (Udacity Submission)

## Dataset

> The dataset consists of information regarding individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There were 183412 entries in this dataset with 16 features. Irrelevant features were dropped to make it 6 features (duration_sec, user_type, member_birth_year, member_gender and AgeGroup). There are two numerical columns and three categorical columns. The AgeGroup column was created to classify the member_birth_year into 5 different categories. very old, Old, midlife, young and very young. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

> In the exploration, I discovered that majority of the users of the rideshare are in the midlife and old ages. There is a moderate amount of users who are young with very little amount of them very young and very old. As for their genders, most of the users are male with less than half of them females and very little amount of them with undisclosed genders. A significantly major part of the users are subscribers with very little amount of them falling into the customer category. I also found that there is a correlation between the time spent on the rideshare and agegroup and that users in the midlife and the old group of the age group spent more time user the ride share than any of the other age groups.


## Key Insights for Presentation

> For the presentation, I focus more on the relationship between the time spent on the rideshare and the gender of the users. I also looked at the agegroup of the users and the relationship with the time spent on the rideshare.

> I use a KDEplot to show the distribution of the user gender and the duration of the bikeshare rides. I also use a KDEplot and a piechart to show the distribution of agegroup of users and the duration o fthe bikeshare rides. Finally, I use a facetgrid to show the corelation between the age group of users and the time spent on the rideshare.


![Ford Dataset](/ford.png)


Kaggle file is [here](https://www.kaggle.com/code/akachimaduako/ford-gobike-system-data-part1), Notebook on GitHub is [here](https://github.com/BlackGuyFawkes/DataScienceNotes/blob/main/ford-gobike-system-data-part1.ipynb). A summary can also be found on my portfolio website [here](https://www.maduakoakachi.com/portfolio#h.n64vs3ijzilo)
