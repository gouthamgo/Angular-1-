# Create a new Angular project using the CLI and run the app. Add bootstrap to the project and run it to make sure that everything works.

- Go to CLI

## to create a new project ng <Projectname>
  
```
cd Desktop
mkdir Projects
cd Projects
ng new Trailwebsite 
```
## now put in code <Project folder name>
  
  - code Newwebsite
  
  ## now use ng serve --o 
  - this creates a local server to host the website 
  ```
  When running the project you will see below error.
  ng : File C:\Users\my pc name\AppData\Roaming\npm\ng.ps cannot be loaded because running scripts is disabled on this system. For more information, see about_Execution_Policies at 
  How to fix this ng.ps cannot be loaded because running scripts is disabled on this system on angular?
  
  Go to your angular project folder on Command line(CMD) and then run the below code. It will be fixed.

  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  ```
  
 ## Adding Bootstrap and Jquery
  
  - npm bootstrap jquery --save
  
  -- go to angular.json file to add
  
  ```
   "styles": [
              "node_modules/bootstrap/dist/css/bootstrap.min.css",
              "src/styles.css"
            ],
            "scripts": [
              "node_modules/bootstrap/dist/js/bootstrap.min.js",
```
 ### Try to use stackblitz to lauch the projects in the live environment 
  
  
  

