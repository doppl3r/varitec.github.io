# About Varitec Solutions
Founded in Phoenix 40 years ago, Climatec grew to more than 850 employees with 13 locations in Arizona, California, Nevada, New Mexico and Texas.

Link: http://varitecsolutions.com

### Development Structure
This website uses jQuery to load static HTML elements to specific pages. To test locally, download the project source and run the index.html from a secure (local/http) server. File:// is not secure.

### Recommended IDE
VSCode
- [download](https://code.visualstudio.com/download)

### Deployment Instructions
Varitec Solutions uses Sass (a stylesheet language) to precompile the global stylesheet. In short, the stylesheet.scss creates a new stylesheet.css that the browser can interpret.

In order to continually compile for deployment, you must install the Node.js Sass library
- [Download](https://nodejs.org/en/download/) & Install Node.js
- Run the following command in the node console: ```npm install -g node-sass```

The project 'tasks.json' file has predefined rules where the .css file will be compiled. Simply build the project by pressing ```ctrl + shift + b``` or enter ```> tasks: run build task``` into the VSCode ```'View' > 'Command Pallete'``` input field. You only need to build if you edit the .scss file.

When you are ready to update the changes to the main varitecsolutions.com website, set up the FTP instructions on your local machine and upload the new code to the root directory.