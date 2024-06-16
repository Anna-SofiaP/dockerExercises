# Cyber Security Base course project

This is a project that was made on the Mooc Cyber Security Base course.
The image for the application has been published to Docker Hub: https://hub.docker.com/r/ansku01/csb-project/tags.

## How to run the application

1. Make sure you have docker installed: https://www.docker.com/get-started/.
2. Open a terminal or a command prompt and navigate to a suitable dorectory where you want to clone the source code of the project.
3. Clone the project from https://github.com/Anna-SofiaP/CSBproject1/tree/main/csproject.
4. Run the command `docker build . -t csbapp`to build the image.
5. Run `docker run -p 8000:8000 csbapp`to start the container.
6. Open a web browser and navigate to http://localhost:8000.

Now you should see a login page. Unfortunalety, you cannot log in to the application.
