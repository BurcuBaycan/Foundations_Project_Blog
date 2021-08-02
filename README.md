# Foundations_Project_Blog
Simple Blog WebApp that allows people to create an account and create blog posts.

Burcu's Blog
This is a blog-posting web app. As the name ımplıes, users can create blog posts and read through blog posts of other people.

##Main Features

Display blog posts and information about them (like author and published date).
After creating an account and logging in users can create Blog posts.
Users can delete their own blog posts but not the ones of other authors.
Users can also comment on other peoples posts.

##Technologies

Flask framework.
Sqlite database locally and postgres database on server.
Python

##Defects
If another user has the same name they can delete the post of another user with the same name.
Users can't edit their posts.
If you update the ratings you gave, the average ratings won't update.
The books on the shelf cannot be deleted.
Reset password part hasn't been implemented.
The book detail page on deployed web app cannot hide excess text in the description.(While it works fine locally)

##Get Started
Clone it to your computer
Create a new folder, change directory into that new folder
git clone <repoURL>
Run the web app using Flask, locally.
Change directory to the repository just cloned.

Point Flask to your application:

macOS/Linux: export FLASK_APP=main.py

Windows: set FLASK_APP=main.py

Run the flask application:

flask run

Open the web app Go http://localhost:5000 in your browser.

Quit the web app Press CTRL+C in terminal

##Sources:
Udemy: 100 Days of Code - The Complete Python Pro Bootcamp for 2021
