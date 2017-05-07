# Webpack-starter-kit
Webpack Install and config 
check for node and npm versions by 
node -v and npm -v 
Initiate the project using npm init and toggle through various option entries

Now install Webpack using
npm i -D webpack //where i -D says to save the dependency

To install webpack globally on your system use
npm -g i webpack

To view webpack versions 
npm view webpack versions --json //to show all versions

Create folder src and dist 
create app.js in src file

Now we bundle the app.js to bundle.js using
webpack ./src/app.js ./dist/app.bundle.js
       //source file