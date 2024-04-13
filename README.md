# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

or Run by docker compose

#Few permissions need to be given
usermod -a -G docker jenkins
 systemctl restart jenkins
 #in shell need this command to be added to automate
docker build . -t node-app
 docker run -d --name node-container -p 8000:8000 node-app

