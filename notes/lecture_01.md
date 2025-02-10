# Anottations
## Terminal Commands
### Node -v -> used for show how node version installed and in use in your system
### nvm ls -> used for show versions installed in your system and version avaiable for install
### nvm --help
### nvm alias default

## Steps of the lecture
### First Step Configure the develop environment using terminal commands to verify version of node installed in your system and install node lts/hydrogen version
### One problemn ocurried... when we start codespaces environment, the node version return to default(20.18.1 or better), we need configure to the default node version be what we choose
#### Executed nvm --help to see the commands avaiables in nvm, used nvm alias default lts/hydrogen to setup the correct node version to ever start on the github codespaces
### Need to create de RunCommands file to setup what configs run when execute npm install be executed
#### created .nvmrc file and writed on she the lts/hydrogen