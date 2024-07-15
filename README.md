# Face-Recognition-Attendance-System
Welcome to the FaceRecognition Attendance System, a  solution for efficient and secure attendance tracking. This system leverages advanced facial recognition technology to streamline the attendance process, making it both accurate and user-friendly. This face Recognition based Attendance system is a Django application written in Python, HTML and CSS


Features: Our website will consist of two distinct pages. 

1. It is available to current students and faculty members.
 • An attendance file is generated after all necessary information is filled out and a group photo is uploaded.
   • After the files have been uploaded and the attendance grading has been finished through the backend, they will be sent to a webpage where they may download the attendance file
  •Faculty members are in charge of adding information and uploading specific photos.
    •The pickle file, which can then be used to record attendance, receives these uploaded photos in the form of encodings.



Directories and Files:

   location.csv - CSV-formatted attendance file
   index.html-Homepage (where group photos can be uploaded)
 login.html - The login page allows you to add  students details. 
 result.html - download page (download attendance file)
  pickle.pkl - File used for storing encodings of individual student
  admin.py -Contains some models
  apps.py -Contains some apps from Django
  forms.py - Contains some forms from Django
  models.py - Models are created here
  urls.py  - File used for handling URLs
  views.py  -File containing all application views
   asgi.py`- Gives ASGI config for Face Recognition Project
   settings.py - Contains Settings for Face Recognition Project
   wsgi.py – Gives WSGI config for Face Recognition Project
   imgs  -Dataset in image format
   media - Stored dataset of images
   db.sqlite3 -Database for storing data
   manage.py - Used for deploying, debugging, or running our website
   requirements.txt  - Contains all python packages


Setting up:

To manually install Python 3.9, visit the official website.

• To install project dependencies, run `py -m pip install -r requirements.txt`.

• Use the command `cd Face_recognition in a new terminal window to access the folder.

• In the project directory, execute the programs `py manage.py makemigrations and `py manage.py migrate' to generate and apply migrations.

• Type `py manage.py runserver to launch the web server.

• It takes some time to generate the URL and process the dataset face encodings.
