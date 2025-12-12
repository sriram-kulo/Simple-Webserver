# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
admin.py

from django.contrib import admin

from models import Employee, EmployeeAdmin admin.site.register(Employee, EmployeeAdmin)
models.py

from django.db import models

from django.contrib import admin

class Employee (models. Model):

eid-models.CharField(max_length=20, primary_key="eid")

name=models.CharField(max_length=100)

salary models. IntegerField()

age models. IntegerField()

email-models. EmailField()

class EmployeeAdmin(admin.ModelAdmin):

list_display=('eid', 'name', 'salary', 'age', 'email')
## OUTPUT:
<img width="1917" height="916" alt="Screenshot 2025-12-01 154900" src="https://github.com/user-attachments/assets/733024ba-5191-4baf-b497-a1495139237c" />


## RESULT:
The program for implementing simple webserver is executed successfully.
