# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
### Clone Repository
Clone the repository to your machine:
```
git clone https://github.com/ObelusFamily/Anythink-Market-gx6yo.git
```

### Install Docker
In order to run the project, it's necessary to install docker.
Use the following link to install it on Linux, MacOS and Windows:
```
https://docs.docker.com/get-docker/
```
### Verify Docker
Verify docker is installed using the following commands in your terminal:
```
docker -v
```
and
```
docker-compose -v
```
### Run Project
From the project root directory run:
```
docker-compose up
```
Test if the project backend is running by opening:
```
http://localhost:3000/api/ping
```
To verify the frontend open:
```
http://localhost:3001/register
```
If everything is working correctly, you should be able to create a new user.


