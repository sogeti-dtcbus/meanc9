     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


# MeanApp

- Designed for Cloud9
- This project was generated with Angular 2, MongoDB, Express and Node
> Install/Update node and npm
- $	nvm install node && nvm alias default node && npm update npm -g
> Install Angular CLI
- $	npm install -g @angular/cli (takes some time)
> Change to the 'mean-app' directory
- npm install (takes some time)
> Setup MongoDB within 'mean-app' directory
- $	sudo apt-get install -y mongodb-org
> Setup Data Storage for MongoDB
- $	mkdir data
- $	echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
- $	chmod a+x mongod
---
- To run the app, ensure you're in the 'mean-app' directory and run the following bash commands on Cloud9:
> runs mongodb in the background
- $	nohup ./mongod &
> build the app
- $	ng build
> start node
- $	node server.js
- Test your MEAN App by going to “Preview > Preview Running Application” You can now view existing posts, add new ones, update existing or delete from your app. You can also copy your c9users.io link and share it—your project is public, so anyone with the link will have access.
