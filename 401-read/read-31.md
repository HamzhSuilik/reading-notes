# Docker

Docker takes away repetitive, mundane configuration tasks and is used throughout the development lifecycle for fast, easy and portable application development - desktop and cloud. Docker’s comprehensive end to end platform includes UIs, CLIs, APIs and security that are engineered to work together across the entire application delivery lifecycle.


Virtual environments allow us to use more than one version of Python on several projects on the same computer, but Docker gives us better options for dealing with different environments.

**Install Docker**
Download the Docker file from this website : 
- `https://www.docker.com/get-started`

After installation check if the version 19 or higher :
`$ docker --version `

Check of installation Docker Compose tool (dditional tool that is automatically included with Mac and Windows downloads of Docker) :
`docker-compose --version `
There is no need to install this tool in windows and Mac , just in Linux , use this command to install the tool :
`sudo pip install docker-compose`

To run the Docker in the terminal use :
`docker run <command>`


An image is a snapshot in time of what a project contains. 
A container is a running instance of the image.

create a Docker file for Docker image :
`$ touch Dockerfile` 
`$ touch docker-compose.yml` 
Dockerfile methods RUN, COPY, and ADD

More than one application can be created in the Django project, and each application will contain 6 important files to run the app :
admin.py is a configuration file for the built-in Django Admin app
apps.py is a configuration file for the app itself
the migrations/ directory stores migrations files for database changes
models.py is where we define our database models
tests.py is for our app-specific tests
views.py is where we handle the request/response logic for our web app


