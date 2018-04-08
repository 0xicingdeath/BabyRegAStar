# BabyRegAStar  

Using a newer blockchain technology for businesses called Hyperledger Fabric, trying to find out how to put birth dates and birth registries on the blockchain.  

## Installation Instructions 

### Mac OS X 

Install node: 
`nvm install --lts`
`nvm use --lts`
`node --version`

Install docker: https://docs.docker.com/docker-for-mac/install/

Install command line tools for Hyperledger Composer: 

`npm install -g composer-cli`

Install REST Server to open RESTful API: 

`npm install -g composer-rest-server`

Hyperledger Utility for generating assets: 

`npm install -g generator-hyperledger-composer`

Install Yeoman to generate applications: 

`npm install -g yo` 

Install playground: 

`npm install -g composer-playground`

Install Hyperledger Fabric: 

```curl -O https://raw.githubusercontent.com/hyperledger/composer-tools/master/packages/fabric-dev-servers/fabric-dev-servers.tar.gz
tar -xvf fabric-dev-servers.tar.gz 
```
Extract to runtime: 

```cd ~/fabric-tools
./downloadFabric.sh
```
Starting and stopping Hyperledger Fabric: 

```
 cd ~/fabric-tools
 ./startFabric.sh
 ./createPeerAdminCard.sh
```

Starting Playground: 

```
composer-playground
```

# Time Spent
  2-4 hours: learning Hyperledger Fabric from the documentation and python examples  

  1-1.5 hours: cleaning up npm and development environment to install Hyperledger composer  

  1 hour: reading documentation about installation and usage of Hyperledger  

  6 hours: writing contract  


