# PLC_Node-RED_Access
Development of Keyence PLC web access based on Node-RED protocol communication

## Setting up the PLC

Upload the file inside for HMI and PLC respectively. The PLC should have been set to KV host mode comunication automaticly.


## node-red installation

1. Installing node.js
    
    Installing node.js in the premise can be done by going to the website and downloading the installer (windows) or by running code below (linux)

    ```
    # installs nvm (Node Version Manager)
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash

    # download and install Node.js (you may need to restart the terminal)
    nvm install 20
    
    # verifies the right Node.js version is in the environment
    node -v # should print `v20.18.0`
    
    # verifies the right npm version is in the environment
    npm -v # should print `10.8.2`
    ```

2. installing node-red
    
    run the code below in terminal

    ```
    sudo npm install -g --unsafe-perm node-red
    ```

## Running flow

1. importing the flow at ```/source/node-red/```
   
    This can be done by accessing the node-red web access GUI. Pressing the 3 bar on top right corner and importing flow.

2. deploy the flow.


