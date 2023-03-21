
# Docker and python(django) 

This is a simple project, for creating docker image and conteiner for Django.




## Installation

Install the project with the git code: Download and follow the instructions

```bash
 https://github.com/Telisman/podcast_docker.git
```

Once the project is copied, open commande.txt file and follow commnands:


```bash
1.docker-compose build
2.docker-compose run --rm app django-admin startproject core .
3.docker-compose up
4.docker exec -it django_container /bin/bash
```

After runing all commnands in your terminal, it will create Docker container: podcast_docker on port 8000 on your local PC. 
It will also create an Docker image and mysql database.

After this you can start working on your django project using Docker container.



## Authors

- [@DavorTelisman](https://github.com/Telisman)


## FAQ

#### Should I have Docker desktop?

You need to have Docker desktop install on your local machine. 



## 🛠 Skills
Python, Django, Docker, MySql, Linux, CMD ...

