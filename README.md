# YaMDB Project
## Description
**REST API** for **YaMDB** service, which stores *reviews* on different *titles*. *Titles* are divided to different *categories* and can extended by admin. 

## Installation
1. clone repository in your local mashine
2. create and activate virtual environment

`python -m venv venv`

`source venv/Scripts/activate`   

3. create and make migrations

`python manage.py makemigrations`

`python manage.py migrate`

4. run project on your local machine

`python manage.py runserver`
