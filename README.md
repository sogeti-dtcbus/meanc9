     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


# MeanApp

- Designed for Cloud9
- Create a new Cloud9 Workspace, add a name and description, then choose 'Clone from Git'
- Enter the following: git@github.com:sogeti-dtcbus/meanc9.git
- Create Workspace
- This project was generated with Angular 2, MongoDB, Express and Node
> Install/Update node and npm
- $	nvm install node && nvm alias default node && npm update npm -g
> Install Angular CLI
- $	npm install -g @angular/cli 
> Change to the 'mean-app' directory and run npm install. This will take some time, a script to run the ng build will fire at the end
- npm install
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
> start node
- $	node server.js
- Test your MEAN App by going to “Preview > Preview Running Application” You can now view existing posts, add new ones, update existing or delete from your app. You can also copy your c9users.io link and share it—your project is public, so anyone with the link will have access.
> If you stop the processes or restart your Workspace, simply run the following to restart the app:
- $	nohup ./mongod &
- $ ng build
- $ node server.js
> If your MongoDB fails due to a bad shutdown, simply run:
- $ ./mongod --repair

