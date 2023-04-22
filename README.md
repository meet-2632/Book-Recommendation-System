# A Book Recommendation System 

Over the last several decades, recommender systems have been more integrated into our daily lives because to the proliferation of online services like YouTube, Amazon, Netflix, and many others. Recommender systems are ubiquitous in today's online experiences, from e-commerce (by suggesting items that may be of interest to purchasers) to online advertising (by suggesting the correct contents, matching users' tastes).

Since our goal is to help readers find new books they'll like, we're exploring several methods for doing so, such as the Popularity-based recommender system and the Collaborative filtering-based recommender system (user-item or item-item). To combat the "cold start" problem—where no data exists on a user's previous purchases—we will use a popularity-based recommender system.

## Objective

The main objective is to create a machine learning model to recommend relevant books to users based on popularity and user interests. In addition to the ML Model prediction, we also have taken into account the book recommendation for a totally new user.

## Live Demo
https://book-rec.azurewebsites.net

## Tech Stacks
<p>
<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="html"/>![Screenshot 2023-04-22 130604](https://user-images.githubusercontent.com/80049664/233770396-3f0df465-d0e7-4ec0-88ba-0c7b2d7e6a4f.png)

<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="css3"/>
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="python"/>
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white" alt="jupyter"/>
</p>

## Dataset Description
Kaggle Link :

	https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

• Books.csv 
Attributes : ISBN, Book-Title, Book-Author, Year-Of-Publication, Publisher, Image-URL-S <br>
  Data Size : 270000 entries

• Rating.csv
Attributes : User-ID, ISBN, Book-Rating (1-10) <br>
Data Size : 1150000 entries

• User.csv
Attributes : User-ID, Location, Age <br>
Data Size : 270000 entries


## Data Pre-processing

• We considered users who have rated more than 200 books. This helped us in data reduction as well as in retaining quality data. <br>
![image](https://user-images.githubusercontent.com/80049664/233770309-8bd387e7-9040-4180-b32f-8c845cd10046.png)
![image](https://user-images.githubusercontent.com/80049664/233770346-7d8121f9-86ed-485f-a158-ab3de8b42671.png)

• We considered books who were rated by more than 50 users. This helped us in data reduction as well as in retaining quality data. <br>
![image](https://user-images.githubusercontent.com/80049664/233770365-fe44566a-e434-4a23-af0e-a4611d470b14.png)
![image](https://user-images.githubusercontent.com/80049664/233770373-2ede9497-879c-45ac-82bb-cdd47994658e.png)

## Snapshots
![ss1-home](https://user-images.githubusercontent.com/80049664/233770387-d040212d-709b-41a5-be19-da90f2bbe7a9.png) 
<hr>

![ss2-recommend](https://user-images.githubusercontent.com/80049664/233770415-3d8660c7-42dc-48f8-a011-a314ffcad247.png) 
<hr>

![ss3-recommend-books](https://user-images.githubusercontent.com/80049664/233770426-e2c5d690-fe30-4a50-80ee-3ea76f7382f5.png)
