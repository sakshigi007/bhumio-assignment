## i3systems file upload and download assignment
### Clone the repository
> git clone https://github.com/sakshigi007/i3systems
### Go to root Folder
> cd fileUploadDownload
### Install Dependencies
> pip install django django-admin
### Start Django app
> python manage.py migrate
### Create Super user for django-admin authentication
> python manage.py create superuser
Fill the credentials field in terminal
### Run Django server
> python manage.oy runserver  
### Go to your browser and copy paste the below URL:
> http://127.0.0.1:8000/admin/?next=/login
Login using the credentials used while creating super user.
### File Upload
Click on Add button under Files Admin section, upload your file and mention title.
Click on Save and file will be uploaded.
### File Download
Go to http://127.0.0.1:8000/ on your browser and download the desired file from the list of all uploaded files.
