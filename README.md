# Ex02 Django ORM Web Application
## Date: 06/10/2025
## NAME: JAIRAM J
## REGISTER NO: 25012221

## AIM
To develop a Django application to store and retrieve data from a Car Inventory Database using Object Relational Mapping(ORM).




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
```
admin.py:

from django.contrib import admin
from .models import Movie,MovieAdmin
admin.site.register(Movie,MovieAdmin)

models.py

from django.db import models
from django.contrib import admin
class Movie(models.Model):
    mid=models.IntegerField()
    mname=models.CharField(max_length=100)
    collection=models.IntegerField()
    year=models.IntegerField()
    rating=models.FloatField()

class MovieAdmin(admin.ModelAdmin):
    list_display=('mid','mname','collection','year','rating')
```



## OUTPUT
<img width="1910" height="928" alt="ORM" src="https://github.com/user-attachments/assets/7a1b4eeb-5e7f-49bd-9b9a-96503165e5cc" />



## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
