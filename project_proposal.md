# Project Proposal - SouthPark(animated sitcom) Recommendation

### Question/Need:

These days, there are bunch of movies or tv series there are out there to watch, yet viewers have a hard time selecting what they should watch. Rather than having
to watch every episodes or seasons there are out there in the tv show, it would be best if they could get a simple recommendation or know beforehand what the episode
is about.

The goal of this project is to build  NLP model(incorporating Topic Modeling and Recommendation System) that can help viewers know what topic each
episode features throughout several seasons.

### Data Description:

The dataset used in this project was from the following github link: [Southpark Dataset](https://github.com/BobAdamsEE/SouthParkData). There are total of 70,896
observations where each row represents script spoken by each character from different seasons and episodes.

Features included in the datset are:
* Season
* Episode
* Character
* Line

### Tools:

* Data Cleaning + EDA of the data
* Pre-processing on the script by seasons/chracters(Tokenization, NLTK, TFIDF, Stemming/Lemmetization...etc)
* Topic Modeling
* Recommendation System

### MVP Goal:

* Tokenized data possibly by different seasons/characters
* Run Topic modeling



