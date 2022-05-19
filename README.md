# Node-How-To

## Create a Node Project
1. Open your terminal/command line

1. Create a new directory with your project

        mkdir project-name
1. Go into your project directory

        cd project-name
1. Initialize NPM
        
        npm init
        (if you just want the default values use:
         npm init -y)
1. If you used the default values create a javascript file titled "index" otherwise use whatever you specified

        touch index.js

1. Write some code in your javascript file then run it to ensure 

        node index.js
---
## Create, Export, and Import your Own Module
1. To create your own module create a new file 

        touch my-module.js
1. ```module.exports``` will create an object that holds the code that will be exported

        module.exports.myFunc = () => console.log("Hello")
1. To import the code from your module define a variable that connects to your module

        const myModule = require('./my-module.js')
1. To access the code use dot notation

        myModule.myFunc()
---
## Node Packages
1. Look up the package you want

1. Follow the installation instructions on package listing
