npm install -g how-to-npm
how-to-npm

Step 00:    Update NPM 
    npm install npm -g
-----------------------------------------    
Step 01:    Dev Enviroment
    -delete json file
    npm init
-----------------------------------------
Step 02:    Login
    npm adduser 
-----------------------------------------    
Step 03:    Start a project
    npm init --scope=webdevkris
-----------------------------------------
Step 04:    Install a Module
    npm install @linclark/pkg
-----------------------------------------    
Step 05:    Listing Dependencies
    npm ls
    how-to-npm verify NOT OK
    npm install @linclark/pkg --save
    how-to-npm verify OK
-----------------------------------------
Step 06:    NPM Test
    -Create a file named test.js
    - replace script info with:
    "scripts": {
        "test": "node test.js"
    },
-----------------------------------------
Step 07:    Package Niceties
    -This steps is already completed
-----------------------------------------
Step 08:    Publish
    npm publish
-----------------------------------------
Step 09:    Version
    -change version number
    npm publish
-----------------------------------------
Step 10:    Publish Again
    -Same as step 9
-----------------------------------------
Step 11:    Dist Tag
    npm dist-tag add @webdevkris/workspace@1.0.1 test
    how-to-npm verify
-----------------------------------------    
Step 12:    Dist-Tag Removal
    npm dist-tag rm @webdevkris/workspace test
    npm dist-tag add @webdevkris/workspace@1.0.1 latest
-----------------------------------------    
Step 13:    Outdated
    how-to-npm verify @linclark/pkg
-----------------------------------------
Step 14     Update
    -remove the following from the package.json file
        "async": "^0.2.10",
        "express": "^3.2.6",
        "socket.io": "^0.9.17"
    npm update
-----------------------------------------
Step 15     Rm
    npm rm @linclark/pkg
    -delete everything in node_modules
-----------------------------------------    
Step 16:    Finale
    