python -m venv movie_venv

cd movie_venv

Scripts\activate

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv>pip install django

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv>django-admin startproject config

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv>rename config backend

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv>cd backend

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>git init
Initialized empty Git repository in C:/Users/2022402/Documents/KopaszBela/movie_venv/backend/.git/

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>code .

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>
(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>pip freeze > requirements.txt

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>git add *

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>git remote add origin https://github.com/KopaszB/elso.git

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>git commit -m "first commit"

(movie_venv) C:\Users\2022402\Documents\KopaszBela\movie_venv\backend>git push -u origin master
