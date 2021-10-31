# Awwards Zone

#### By Floice Nyota Ndiiya

---
# Description  
This is a Django web application that allows users to view posted projects and their details. 
  
---
## User Stories  
User Can :-

* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects 
* View projects overall score
* View my profile page 

---
## Access the website
Need the latest browser to be able to View

Follow this link https://awwards-zonenyota.herokuapp.com/

It is hosted by heroku

---

## Setup and Installation  
To get the project .......  
  
##### Clone Repository:  
 ```bash 
https://github.com/FloiceNyota98/Awwards-Zone.git
```
##### Install and activate Virtual Enviroment virtual  
 ```bash 
cd Awwards-Zone && python3 -m venv virtual && source virtual/bin/activate 
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
##### Setup Database  
  SetUp Database User,Password, Host then following Command  
 ```bash 
python manage.py makemigrations awwards_app 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run Application  
 ```bash 
 python3 manage.py server 
```
##### Test Application  
 ```bash 
 python manage.py test photo
```
Open the application on your browser `127.0.0.1:8000`.  

---

## API
### Get all Projects -> [see json list here](https://awwards-zonenyota.herokuapp.com/api/projects/?format=json)

### Get all Profiles -> [see json list here](https://awwards-zonenyota.herokuapp.com/api/profiles/?format=json)

---
  
## Technology used  
  
* HTML, CSS, Bootstrap

* Git

* Python, Django Framework

* Heroku 
  
  
## Bugs  
* It may take a while to load due to the size of the photos
  
## Contact Details
nyotafloice@gmail.com

@FloiceNyota (Twitter)

@Floice Nyota `Slack Moringa`

---

### License
This Project is under the [MIT](LICENSE) license