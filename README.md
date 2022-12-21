# ds-container
Data Science Base Container - Python, Anaconda, JupyterLab

## Purpose
This repository is the base level project strucutre for data science projects using Docker and Docker Compose for the environment management. The files in this repo are the baseline requirements for getting a project up and running.

## Using This Template

This template assumes that you have the Docker Daemon up and running on your local machine. If you need any assistance with this part of the process, visit the [Docker documentation](https://www.docker.com/get-started/).

Use the following steps to get up and running with this template:

1. Click on "Use this template" on the upper right hand side of the screen
2. Name and fill out the repository form and create the new repository from this template
3. Clone the repository to your local machine into a working folder
4. Update the `Dockerfile` with any needed libraries under the `RUN` command
5. Run the command: `docker compose up`. This will build the image from the Dockerfile and launch Jupyter Lab
6. Copy the link from the command output and paste it into a browser
7. Use Jupyter lab to create notebooks all within the Docker environment

If you experience any issues downloading and using this template, please feel free to open up an issue within this repo.

## Upcoming Features

This project serves as a base template. I designed it to fit my specific workflow in starting a new project. There are always changes and customizations being made on a case-by-case basis. That being said, I have a few features I am planning to add:

1. More comprehensive list of data science and scientific computing libraries
2. Built in SQL image for tabular data

I will update this list as changes are implemented and new changes are added to the list.  
