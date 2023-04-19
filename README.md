# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

CLone the repository to thea idea. start a new inside the project folder.

### STEP 2:

Type the appropriate code for your table and provide appropriate datatypes to the columns.

### STEP 3:

Create a report about project in readme.md file and upload the django-orm -app folder to your remote repository.

## PROGRAM
```
from django.db import models
from django.contrib import admin


# Create your models here.
class Student (models.Model):
    referencenumber=models.CharField(max_length=20,help_text="reference number")
    name=models.CharField(max_length=100)
    age=models.IntegerField()
    email=models.EmailField()
    salary=models.IntegerField()

class StudentAdmin(admin.ModelAdmin):
    list_display=('referencenumber','name','age','email','salary')
```

## OUTPUT
(/home/sec/Pictures/Screenshots/out.png)


## RESULT

Thus the project is developed to have Student information database.
