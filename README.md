## Docker Assignment - Agile Software Practice.

__Name:__ Brendan O'Connor

__Demo:__ https://youtu.be/Nj9PI4ZMtuE

This repository contains the containerization of the mukti-container application illustrated below.

![](./images/arch.png)

### Database Seeding.

- I added a new service called "seeding" that uses the same mongo image as the database.
- I used the command field to do a mongoimport.
- I used a bind mount to attach the seeding.json to the container.

### Multi-Stack.

- I added a compose profile to the database seeding and the express web app

### Extra.

- I installed ping utility on running mongo container to check isolation.