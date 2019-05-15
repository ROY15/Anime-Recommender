# Anime-Recommender

Recommender is about recommending anime shows to user. 
Recommender is design using Flask Framework with 3 different algorithm for different ways to get recommendation.


we can to download data fromhttps://www.kaggle.com/CooperUnion/anime-recommendations-database this site.

install packages from Anaconda Navigator Environments:

flask

sklearn

Way to run this code:

It contains Python file, in statics folder we have images and CSS files ,template folder contains html files and in Anime_data folder have data files.

Please run this code in Spyder and in FireFox enter this  http://127.0.0.1:5001/ in address bar.

*Due to large file size, many operations and timeout it takes to time to load on web browser.
 (So need to refresh page again and again until it loads.) 
Steps to run code

•	Here we have to run app.py files.

•	In first page enter user id as ‘admin’; if you enter ‘admin’ then you will get all plots related to our project.

•	Otherwise enter user id between 1 to 73515.

•	Then you will get user page which will have two slider with anime images  and their names and if you click on them we will be directed to anime details page.

•	In that 1st slider will have recommendation base on Apriori algorithm and 2nd slider will have recommended using k-mean 
In anime details page it contains details of the selected anime like Genre, rating, Type of transmission, members and episodes, based on these you will get recommendations.

