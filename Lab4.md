# Lab4

## Question 1

https://github.com/TurnipXenon/CMPUT404-Lab4-Django

## Question 2

It shows the deault django project page that says "The install worked
successfully! Congratulations!"

## Question 3

Going to `/` gets you a 404 Page not found error.

Going to `/polls` gets you a page that says "Hellow world. You're at the polls index."

## Question 4

Django migration allows models to be represented into your database. You need to do
this whenever any changes are made to your models, so that the database reflects
the changes you made to your code.

## Question 5

The DJando admin site shows authentication related entries, like users, such as
the current super user. It also shows the models under the polls app. You can get
a custom model to show up in the Django admin page by registering it to the admin
site in `admin.py`.

## Question 6

- You see a page that says "You're looking at question 38." at `/polls/38`.
- You see a page that says "You're looking at the results of question 38." at
`/polls/38/results`.
- You see a page that says "You're voting on question 38." at `/polls/38/vote`.

## Question 7

urls are provided by the function's render. It's very easy to put the wrong url
or having to edit the hardcoded url whenever changes are made in the function.

## Question 8

Generic views take up less code, and it makes views more readable. If you're using
a template or possibly a common patttern, use generic views. Otherwise, if it's
simple or none of your use case fits the give generic views, don't use generic views.