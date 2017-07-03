# Intro to APIs
---

Our application is going to be a simple task manager that will be divided into two projects: API and web app.

Our API will be called NTask (Node Task) and it will have the following features:

- List of tasks.
- Create, delete, and update a task.
- Create, delete, and update user data.
- User authentication.
- API documentation page.

___

## Get start with :

 1. Create the project :
 ```bash
 mkdir ntask-api
 cd ntask-api
 npm init
 ```
 2. install dependencies :

 `npm i babel-cli babel-preset-es2015 babel-preset-stage-2 babel-register --save-dev`

 3. create `.babelrc`:

 ```javascript
 {
   "presets" : ["es2015", "stage-2"]
 }
```
