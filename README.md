# DOCKER_PROJECT_IIECRISE
# ABOUT PROJECT :
Here, I have created project for wordpress docker compose . WordPress is an open-source website creation platform that is written in PHP and uses a MySQL database. In non-geek speak, it's probably the easiest and most powerful blogging and website content management system (or CMS) in existence today. WordPress is an excellent website platform for a variety of websites.I have used SSH putty by launching an instance on AWS for this project 

# REQUIREMENTS
Docker installation,docker compose installation,launch an instance on aws,login to SSh putty

# ABOUT DOCKER
Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package.

# DOCKER_COMPOSE
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application's services. Then, with a single command, you create and start all the services from your configuration. ... Run docker-compose up and Compose starts and runs your entire app.

# IMAGES_REQUIRED
-mysql:5.7 , wordpress:latest

# STEPS
1.login to aws console and create a instance
```
-launch a instance on AWS EC2
```
2.Copy Instance ip
```
-copy ip and login to putty as a EC2 user
```
3.Come to the root user
```
sudo su
```
4.Update yum
```
yum update -y
```
5.Install Docker
```
yum install docker -y
```
6.Create a directory and move in
```
mkdir compose
cd compose
```
7.Open docker-compose file with yml extension
```
nano docker-compose.yml
```
Write the code and save it and enter
Run the docker-compose file
```
docker-compose up
```
```
Run the ip with the port enabled and your home page will appear
```

# DOCKER_COMPOSE_UP
Docker Compose is used to run multiple containers as a single service. For example, suppose you had an application which required WORDPRESS and MySQL, you could create one file which would start both the containers as a service without the need to start each one separately

# CONCLUSION
Docker compose is a fantastic tool to deploy containers and microservices.We here successfully launched wordpress using docker compose tool and further the data will be save in mysql database with persistent storage
