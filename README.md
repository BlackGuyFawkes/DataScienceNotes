# DataScienceNotes
Data Science Notebooks from Kaggle

# 1. Netflix Movie Database Analysis
## by Maduako Akachi


## Dataset

> The dataset contains details of movies released on Netflix from 2008 to 2021. There were 7789 entries in this dataset with 11 features. During the cleanup process, more features were added namely, Year, minutes and units to make it 14 features. A new dataframe had to be created where all null values were dropped. I got this dataset from Data Science Lovers on Youtube. The dataset can be found here (https://drive.google.com/file/d/1p630pDcSkbQp_WXig8PeEVevZtSo4GQK/view). Several questions were asked during the course of this analysis, they include, 
> For 'House of Cards', what is the Show Id and Who is the Director of this show ?
> In which year the highest number of the TV Shows & Movies were released ? Show with Bar Graph.
> How many Movies & TV Shows are in the dataset ? Show with Bar Graph.
> Show all the Movies that were released in year 2000.
> Show only the Titles of all TV Shows that were released in India only.
> Show Top 10 Directors, who gave the highest number of TV Shows & Movies to Netflix ?
> Show all the Records, where "Category is Movie and Type is Comedies" or "Country is United Kingdom".
> In how many movies/shows, Tom Cruise was cast ?
> What are the different Ratings defined by Netflix ?
> How many Movies got the 'TV-14' rating, in Canada ?
> How many TV Shows got the 'R' rating, after year 2018 ?
> What is the maximum duration of a Movie/Show on Netflix ?
> Which individual country has the Highest No. of TV Shows ?
> How can we sort the dataset by Year ?


## Summary of Findings

> In the exploration, I discovered that the answers to the questions asked. House of Cards had the show ID of s2833 and was directed by Robin Wright, David Fincher, ect. 2019 was the year highest number of movies and tv shows was released. There are also a total of 5377 movies and 2410 tv shows. These and many more answered were discovered. All question were answered correctly using different methods. 





# 2. TMDB Movie Data Analysis
## by Maduako Akachi


## Dataset

> The dataset consists of contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. There were 10866 entries in this dataset with 21 features. Irrelevant features ('imdb_id', 'homepage', 'tagline', 'overview', 'production_companies', 'keywords') were dropped to make it 15 features. There are 6 numerical columns and 9 categorical columns. The Genre column was split to give individual genre values. The dataset can be found here: https://www.kaggle.com/datasets/afsarjan23/tmdb-movies-dataset


## Summary of Findings

> In the exploration, I discovered that Action, Adventure, Science Fiction, Thriller are the most popular movie genres. I also discovered, by plotting several scatter plots how much revenue was produced over the years.





# 3. Wrangling and Analyze Data
## by Maduako Akachi


## Dataset

> Here we have 3 different datasets which with different pieces of infomation. The dataset consists of information regarding individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There were 183412 entries in this dataset with 16 features. Irrelevant features were dropped to make it 6 features (duration_sec, user_type, member_birth_year, member_gender and AgeGroup). There are two numerical columns and three categorical columns. The AgeGroup column was created to classify the member_birth_year into 5 different categories. very old, Old, midlife, young and very young. The dataset can be found here: https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Summary of Findings

> In the exploration, I discovered that majority of the users of the rideshare are in the midlife and old ages. There is a moderate amount of users who are young with very little amount of them very young and very old. As for their genders, most of the users are male with less than half of them females and very little amount of them with undisclosed genders. A significantly major part of the users are subscribers with very little amount of them falling into the customer category. I also found that there is a correlation between the time spent on the rideshare and agegroup and that users in the midlife and the old group of the age group spent more time user the ride share than any of the other age groups.





# 4. clientIdentity
## by Maduako Akachi


## Dataset

> The dataset consists of information regarding Introduction about users from an online database. It is a very small dataset with just 30 entries and 11 features. The data had already been cleaned prior to download, so there was any additional transformation done. The dataset can be found here: 


## Summary of Findings

> In the exploration, I discovered that California (CA) had the largest number of clients with 6 clients. 





# 5. CustomerAndBasket
## by Maduako Akachi


## Dataset

> Here we have 2 different datasets which with different pieces of infomation. The first dataset consists of information regarding the basket used in the store. There were 15000 entries in this dataset with 4 features. The second dataset consists of information regarding the customer. This dataset had 20000 entries 4 features. There were no missing values or duplicates in both datasets, but the customer gae in teh customer dataset had to be converted to whole numbers. Both datasets contained three numerical columns and one categorical columns. Outliers were dropped using the IQR method. The dataset can be found here: 


## Summary of Findings

> In the exploration, I discovered that 
