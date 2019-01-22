# React JS

It is a Javascript liberary.
For Example
In  a webbb page we have components in the web page
React JS use these componeents and bbuilld these coomponeents again with JS and reuse the code..

## Difference Between Angular JS and REact JS
React JS is a libebbracy which is used to design the compoonents oof the web page..
whereas Angular JS is a framework which allows you to bbuild a single page applications 
Angular2 is a ruter whhich uses for form validation it provides the routing too the web page Angular2 uses only one view to handle and send to the server whereas reactjs also made single page applications but we can use multiple vviews.
ReactJS can be used where we need multiple views.

## lets get Started with ReactJS and setup
So to get started create a folder for yur project and init node package manager in it.
```javascript
npm init
```
and just create a new project with MIT licence

After that yoou need to install some packages
```javascript
npm install react react-dom --save
```
save argument is to tell node package manager to go with the production level dependencies.

```javascript
npm install webpack webpack webpack-dev-server babel-loader babel-preset-es2015 babel-preset-react babel-preset-stage-2 --save-dev
```
So here we have lots of stuff going on 
**webpack** :- we need a server which handles the http request since we cannot use our browser because we need soomething to handle http request and browser will work as file server only.

**webpack-dev-server** :- This is again for the setup of the development server the server is setuped for the development process only.

**babel-loader** :- We need babel for handling the es6 stuff and convert them to es5

**babel-preset-es2015** :- This is used to convert the data from es6 to es5 since not all browsers support es6.

**babel-preset-react** :- This is for manageing the react stuff with babel

**babel-preset-stage-2** :- This is for the presets for stage2

**--save-dev** :- This is to inform node package manager that this is a development enviorment code.
