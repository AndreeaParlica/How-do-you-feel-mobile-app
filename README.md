# How do you feel mobile app

A simple mobile app with the scope of practicing python, guided by Udemy course "The Python Mega Course: Build 10 Real World Applications" by Ardit Sulce

## App description

User can login in with a username and a password already created or can sing up to create new credentials
Once he is logged in, he can type a feeling like sad, happy or unloved and the app will generate and display a quote randomly from a file database.

##Technologies

- backend - python
  - modules: datetime, json, glob, random, pathlib, hoverable
- frontend - kivy library
  - modules: app, uix, lang, screenmanager, image,

##Status

The app has the following specifications:
- login features
- checking the correct username and password in a the json database
- restriction with the username and the password are not in the json database
- restrictions when inserting a feeling, if the user does not insert a feeling or the feeling is not in the database files, a message will be displayed
- logout features with going back to the login app automatically
- design features: scrollbar if the quote is to long

## Optimisation - to do list

- activate the button "Forgot your password", currently is inactive
- design reviewing 
- add more file database regarding the feeling which can be inserted, expand the range of feelings the user can insert
