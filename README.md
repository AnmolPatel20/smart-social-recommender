# smart-social-recommender
A Jupyter Notebook project for cleaning social network data and generating smart recommendations for friends and pages based on user connections and interests.


# Social Network Data Processing and Recommendation System

This Jupyter Notebook project analyzes and processes social network data, displaying users and their connections, cleaning the data, and recommending friends and pages based on mutual connections and interests.

## 🧠 Features

- **Display Users and Connections**: Visualizes each user's friends and liked pages.
- **Data Cleaning**: 
  - Removes users with empty names.
  - Deduplicates friend lists and page entries.
  - Filters out inactive users.
- **Friend Recommendations**: Suggests users based on mutual friends.
- **Page Recommendations**: Recommends pages based on common interests.

## 📒 Notebook Files

- `01_introduction.ipynb`: Shows user relationships and page information.
- `02_data_cleaning.ipynb`: Cleans and saves the dataset to a new file.
- `03_people_you_may_know.ipynb`: Recommends users you may know.
- `04_pages_you_may_like.ipynb`: Recommends pages you might like.

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- JSON (for data storage and manipulation)

## 📁 Data Files

- `data2.json`: Raw dataset.
- `cleaned_data.json`: Output of cleaned dataset.
- `massive_data.json`: Used for generating recommendations.
