# Youtube Downloader

Youtube Downloader is a Python Web application built with Django.

[![Heroku](https://heroku-badge.herokuapp.com/?app=heroku-badge)](https://ytdlnaz.herokuapp.com/)
[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fytdlnaz.herokuapp.com)](https://ytdlnaz.herokuapp.com/) 
![Contributors](https://img.shields.io/github/contributors/nasbeer/YouTube-Downloader) 
[![License](https://img.shields.io/github/license/nasbeer/YouTube-Downloader)](http://opensource.org/licenses/MIT)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/nasbeer/YouTube-Downloader/)


# FEATURES!

  - Download Youtube videos in every format ranging rom 144p to Full HD.
  - Easy to use, user friendly UI.


# REQUIREMENTS
  - This App Uses Python 3.7, Django 3.1.1, youtube-dl.
  * If you face server error 500, just upgrade youtube-dl by ```pip install youtube-dl --upgrade```

# INSTALLATION

Install the dependencies and devDependencies and start the server.

```sh
$ git clone https://github.com/nasbeer/YouTube-Downloader.git
$ cd Youtube-Downloader
$ pip install -r requirements.txt
$ python manage.py runserver
```

# DOCKER
```sh
$docker-compose up --build
```
The application will be available at : localhost:8000

If you want to change the port, just change it in the ```docker-compose.yml``` file.
# LICENSE
MIT License
