# markupBoilplate
### created by Vadym Semenets
### FRONTEND WEB DEVELOPER at UranCompany

Welcome to HTMLBoilplate page!

It is a small and hot boilplate which allows you to quick start to develop html/css/sass project.
It uses gulp task-runner as well.

For quick start you need to fork this repository and then execute few commands.

```
  npm install 
```

After executing this command you will see npm_modules folder in your project. Next one will be:

```
  bower install
```

This command will installed all packages for frontend part of your project. It is jquery library on default. All next packages 
you will need you might to install by command:

```
  bower install <package name> --save
```
Congratulations! You have all modules on your local machine in order to start to work!
To run your project on localhost you need to run gulp command. Let's go!

```
  gulp
```
ENJOY!


-----------------------------------------------------------------------------------------------------------
  STRUCTURE OF THE PROJECT
      
```
├── dist
│   ├── css
│   │   └── main.css
│   ├── js
│   │   └── main.js
│   ├── img
│   └── index.html
|
├── src
│   ├── img
│   ├── js
|   |   └── app.js 
|   |   └── main.js  // includes imports of all .js files from js catalog
│   ├── style
|   |     └── base
|   |     |     └── _reset.scss
|   |     └── main.scss // includes imports of all .scss files from style catalog
│   ├── partials
|   |     └── _header.html
|   |     └── _footer.html
│   └── index.html
|
├── bower_components
├── node_modules
├── gulpfile.js
├── package.json
└── .gitignore
```

The project includes 2 folders only. There are src and dist folders. You will work in src folder only. dist folder contains compiled and minified code you had written in files from src folder. Compilling, minification, image compression and other tasks executes our gulp runner.
