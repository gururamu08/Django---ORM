# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

### THEME PARK Entity Diagram
![entity](/info.jpg)

## DESIGN STEPS

### STEP 1:
Clone the repository to theia ide. start a new app inside the project folder.

### STEP 2:
Type the appropriate code for your table and provide appropriate data types to the columns.

### STEP 3:
Create a report about your project in readme.md file and upload the django.orm.app folder to your remote repository.


## PROGRAM
```
from django.db import models
from django.contrib import admin
# Create your models here.
class Themepark(models.Model):
    Ticketno =models.IntegerField(primary_key=True,help_text="Ticketno")
    Name =models.CharField(max_length=100)
    age =models.IntegerField()
    NoOfFamilymembers =models.IntegerField()
    intime =models.IntegerField()
class Themeparkinfo(admin.ModelAdmin):
    list_display =('Ticketno','Name','age','NoOfFamilymembers','intime')    

```

## OUTPUT

![django-ORM](/Screenshot_20230112_072815.png)


## RESULT
Thus the project is developed to have Theme park information database