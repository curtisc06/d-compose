# d-compose
Sample docker compose project that utilizes a frontend app that runs is a web browser which communicates with a backend API.  
The backend API stores and retrieves data from a mongo db.

There are three containers (services) - frontend, backend and one for the mongo db.  Each image is used to start dedicated containers for each service. 
Only two images are provided since the mongo db image is already available in dockerhub.

Docker compose is utilized to start three containers - one for each image.  Docker compose allows us to avoid remembering all of the "docker run" 
commands that would be required without docker compose.    
Alternatively, each container can be started manually without docker compose by using docker run commands.  Those commands can be founds in 
"docker run commands.txt"
