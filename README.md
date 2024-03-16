1. ## Setup react project
Create Node project
* npm init --y

2. ## Install Babel dependencies 
* Babel is a compiler that converts your modern Javascript into backward- compatible version to be supported by older browsers or environments. 
* In React, we use the JSX syntax and which is a special kind of JavaScript that combines Javascript and HTML. The JSX syntax is not supported by some older browsers so it would not work, That's wy we need Babel to convert it into versions that would be supported.

* npm install --save-dev @babel/core babel-loader @babel/cli @babel/preset-env @babel/preset-react

3. ## Install Webpack dependencies
Webpack is a static module bundler for modern javascript applications.It can take differenr files and bundles them into a single Javascript file. 
#### npm install --save-dev webpack webpack-cli webpack-dev-server

4. ## Install HtmlWebpackPlugin
The HtmlWebpackPlugin is the package that simplifies the creation of HTML files to serve your Webpack bundles. as mentioned above when Webpack bundles all our files, it can generate a single JavaScript (known as a bundle) that will be served along our HTML file.
#### npm install --save-dev html-webpack-plugin


5. ## Install React dependencies
#### npm install react react-dom 

6. ## Add React files
* create a public folder and in the created folder create an index.html file
* create an src folder and in it create an App.js file and add the following code
* Back in the root folder create an index.js which will be the entry of our app. add the following code (You can also create this index.js in the src folder and if you do so remember to update the path to match yours)

7. ## configure Babel
* In the root folder create a file named .babelrc and add the following code

8. ## configure Webpack
* Create a file named webpack.config.js and add the following code

9. ## add scripts in package.json
* in the package.json file in the scripts object scripts that will be used to run Webpack and start our application
add scripts as mentioned below

10. ## start your application
run npm start to start the application