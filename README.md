# Ex02 Django ORM Web Application
## Date: 20-03-24

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
from django.db import models

from django.contrib import admin

class Book(models.Model

    SNO=models.IntegerField()
    
    NAME=models.CharField(max_length=100)
    
    PRICE=models.IntegerField()
    
    AUTHOR=models.CharField(max_length=100)
    
    
 
class BookAdmin(admin.ModelAdmin):

    list_display=('SNO','NAME','PRICE','AUTHOR')


## OUTPUT
![web exp2](https://github.com/KiranbalajiH/ORM/assets/149135475/e2e8e5ea-f2da-4892-86d2-5cfa3ac5e1b0)




## RESULT
Thus the program for creating a database using ORM hass been executed successfully
