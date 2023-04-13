# webpack starter template

This is a simple webpack template to quick start your projects without the hassle of manually setting up webpack each time you start a new project.

# Get started

# webpack setup

1- create a package.json file with node package manager (npm)

`npm init -y`

2- Install webpack locally and install webpack-cli (webpack-cli will allow to run webpack from command line)

`npm install webpack webpack-cli --save-dev`

**Note** we are installing the above dependencies as dev dependencies (--save-dev) because they are only required by us as developers when we are developing the application. They will not be required in the app launched in production.

3- Create your html and js files. You can follow the following folder structure

project
|- package.json
|- package-lock.json
|- /dist
|- index.html
|- /src
|- index.js

write some code, link the 2 files and then in the command line run

`npx webpack`

this will create the bundle file for you
