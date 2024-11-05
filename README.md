## Docker Assignment - Agile Software Practice.

__Name:__ Brendan O'Connor

__Demo:__ .... The link to your YouTube demonstration ....

This repository contains the containerization of the mukti-container application illustrated below.

![](./images/arch.png)

### Database Seeding.

- I added a new service called "seeding" that uses the same mongo image as the database.
- I used the command field to do a mongoimport.
- I used a bind mount to attach the seeding.json to the container.

### Multi-Stack.

[Briefly explain how you support building development and production stack options.]

### Extra.

- Installed ping utility on running mongo container to check isolation.