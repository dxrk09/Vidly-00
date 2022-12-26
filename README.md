# Getting Started with Create React App

This project was bootstrapped with [Create React App].

# Informations about the project

A CRUD movie database application that allows users to create movie listings. Users are able to update a movies, like, and even search for a movie. Only logged in users are able to make any changes to the movies.


# The technologies used

+ JavaScript
+ CSS3
+ HTML5
+ MongoDB(Mongoose)
+ Node.js
+ Express
+ React
+ Bootstrap
+ Heroku

# Pre-requisites

You need to have Docker Engine and Docker Compose on your machine. You can either:

| Operating System     | Installation  |
| -------------        | ------------- |
| Mac                  | [Mac Docs](https://docs.docker.com/desktop/install/mac-install/)  |
| Windows              | [Win Docs](https://docs.docker.com/desktop/install/windows-install/)  |
| Linux                | [Linux Docs](https://docs.docker.com/desktop/install/linux-install/)  |


# Available Scripts

__In the project directory, you can run:__


Run the app on containers :

```
$ docker-compose up
```
>Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

Start the containers on the background :

```
$ docker-compose up -d
```

List the containers relevant to this app :

```
$ docker-compose ps
```

Stop and removes the containers :

```
$ docker-compose down
```

***


__To check the communication between containers, you can run:__

Login as user :
```
$ docker exec -it [CONTAINER ID] sh
``` 
Login as root :
```
$ docker exec -it -u root [CONTAINER ID] sh
```

In terminal: 
```
$ ping [service_name]
``` 
### Example:
```
 $ ping api (from web shell container)
or
 $ ping web (from api shell container)
```
