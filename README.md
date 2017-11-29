# csci215_semester_presentations

## Basic Node.JS

### Node in terminal
The Node.JS console is started after installation by typing `node` into the terminal.
This effectively starts a console similar to the JS console that runs in the browser.
```
$ node
$ > console.log('hello');
$ > hello
```

Node can also run JavaScript files by using `node filename.js`
Running the example file that starts an http server would be 
```
$ node hello.js

```

### Node Package Manager
Node projects can be managed with Node Package Manager (NPM)
NPM is a package manager and dependency manager that allows the addition of other JavaScript libraries i.e. Express or Angular. This is acomplished with `npm install package-name`

NPM also allows the ability to specificy build and deployment instructions for a particular application with the package.json, so all dependencies can be tracked and installed form package.json and installed or updated with `npm install` and `npm update`
Running most Node projects can be done with `npm start` 
