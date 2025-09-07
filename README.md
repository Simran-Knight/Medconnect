# Medconnect

## TABLE OF CONTENT 
-[INSTALLATION](#setup_and_installation)

## Setup and Installations
Step to build project and some installation:
```
1) create a folder :
-   mkdir <folder_name>
eg: - mkdir mypro
-   cd  <folder_name>
eg :- cd mypro

2) Inside mypro , create a virtual environment
-    python3 -m venv <virtual_env_name>
eg - python3 -m venv pro

3) activate the virtual env
-   source <virtual_env>/bin/activate
eg - source pro/bin/activate

4) Install Django 
-   python3 -m pip install Django
-   pip install psycopg2-binary

```

## Create Project and Apps  
```
1)Inside mypro , Create project
- django-admin startproject Meconnect

2) Inside Medconnect folder , create apps for the project
-   python3 manage.py startapp user_patient

-   python3 manage.py startapp doctor

3) create Readme.md

4) reqiurements.txt 
pip freeze > requirements.txt








