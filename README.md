# angular2-quickstart
Original tutorial: https://angular.io/docs/ts/latest/quickstart.html

Step to build and run an angular 2 app:

<h1>prerequisite: install nodejs & npm</h1>
- Download & install nodejs newest version (https://nodejs.org/en/download/)
- Open Windows console (Window + R, type "cmd" and press Enter)
- In console, type "npm install npm -g" to install npm:


    $ npm install npm -g

# create & setup project

1/ Create our project folder, mine is "angular2-quickstart"

2/ Add package definition and configuration files:
  + package.json: lists packages the QuickStart app depends on and defines some useful scripts.
  + tsconfig.json: TypeScript compiler configuration file.
  + typing.json: identifies TypeScript definition files.
  + systemjs.config.js: the SystemJS configuration file.
  
*Note: 
  + In this step, you may create all files and folders manually, see it on repository
  + In "systemjs.config.js", you should modify "map" and "packages" json object to match your files and folders on your project

3/ We install the packages listed in package.json using npm. Enter the following command in a terminal window (command window in Windows):

    $ npm install

This command will create whole folder "node_modules".

# build & run project
## A. Using basic npm & javascript config

## B. Using gulpfile.js

If you want to use gulp in your project, then you don't need to add "systemjs.config.js" file, but "gulpfile.js" instead. (See gulp file above)
Reference: https://css-tricks.com/gulp-for-beginners/#article-header-id-5

1/  Install gulp

    `$ npm install gulp --save-dev`

2/ Install necessary gulp libraries

    `$ npm install --save-dev gulp-webserver`
    
    `$ npm install --save-dev gulp-typescript`
    
    `$ npm install --save-dev gulp-sourcemaps`
    
3/ Run gulp
    `$ gulp`

