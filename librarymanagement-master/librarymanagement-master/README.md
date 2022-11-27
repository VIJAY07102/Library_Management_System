# Library Management
## screenshots
### Homepage
![homepage snap](https://github.com/sumitkumar1503/library_management/blob/master/static/screenshots/homepage.png?raw=true)
### Admin Dashboard
![dashboard snap](https://github.com/sumitkumar1503/library_management/blob/master/static/screenshots/adminhomepage.png?raw=true)
---
## Functions
### Admin
- Create Admin account and Login.
- Can Add, View, Book
- Can Issue Book (added by Admin) to registered student.
- Can view Issued book with issued date and expiry date.
- Can view Fine (10 rupees for each day after expiry date).
- Can View Students that are registered into system.

### Student
- Create account and Login.
- Can view their issued book only with expiry date and fine(if there any otherwise 0)
---

## HOW TO RUN THIS PROJECT
### To Run without Docker
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```

- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```
### To Run with Docker
- Install Docker Engine and Docker compose
- Move to project folder in Terminal. Then run following Command :
```
docker-compose up -d
```
- Then, it will prompt you to create username and password, it is for creating the Django superuser
## CHANGES REQUIRED before running the app
Change the settings.example.py file to settings.py file
- And you have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```


## Feedback
Any suggestion and feedback is welcome. You can message me on linkedin
- [Contact on LinkedIn](https://www.linkedin.com/in/vijay-p-669675128)
