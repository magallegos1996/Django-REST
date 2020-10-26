# Django REST
### Based on: [Django REST Framework Tutorial](https://www.django-rest-framework.org/tutorial/1-serialization/)
 
 ### How to run the the project
 
 First, clone this repository with the following command:
 ```sh
$ git clone https://github.com/magallegos1996/Django-REST.git
```
Once you've cloned this repo, please change to the root directory:
 ```sh
$ cd Django-REST
```
Then, execute the following command to create a python virtual environment
 ```sh
$ py -m venv env
```
This will create a directory called  ```cd env```. Enter to this directory using the following command
 ```sh
$ cd env
```
Next, execute the  ```activate.bat``` that is inside the ```Scripts``` directory. Please, follow this steps.
 ```sh
$ cd Scripts
$ activate.bat
```
Now, you have to return to ```Django-REST``` folder so you can install all the requirements needed to run this project. In order to do so, from the ```Django-REST``` directory, execute this.
 ```sh
$ pip install -r requirements.txt
```
Also, you will have to install Django Rest Framework manually.
 ```sh
$ pip install djangorestframework
```
At this point, you will be able to run the project. But first, you have to do some additional steps. 

Place yourself into ```tutorial``` directory
 ```sh
$ cd tutorial
```
Run the following command to make migrations
 ```sh
$ py manage.py makemigrations
```
Then, run those migrations throught this command
```sh
$ py manage.py migrate
```
And finally, run the server with the follwing command
 ```sh
py manage.py runserver
```
Open your browser and go to: http://localhost:8000/

You will need this credentials to get access to the full demo

* **Username:** marcelo
* **Password:** Ioet.1000
