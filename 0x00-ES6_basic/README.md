## Setup
### Install NodeJS 12.11.x
```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```
```
nodejs -v
#v12.11.1
npm -v
#6.11.3
```

### Install Jest, Babel, and ESLint
in your project directory, install Jest, Babel and ESList by using the supplied ```package.json``` and run ```npm install``` .

### Configuration files
Add the files below to your project directory

```package.json```
```babel.config.js```
```.eslintrc.js```

### Finally…
Don’t forget to run ```npm install``` from the terminal of your project folder to install all necessary project dependencies.

### Tasks
- 0. Const or let?
- 1. Block Scope
- 2. Arrow functions
- 3. Parameter defaults
- 4. Rest parameter syntax for functions
- 5. The wonders of spread syntax
- 6. Take advantage of template literals
- 7. Object property value shorthand syntax
- 8. No need to create empty objects before adding in properties
- 9. ES6 method properties
- 10. For...of Loops
- 11. Iterator
- 12. Let's create a report object
- 13. Iterating through report objects
- 14. Iterate through object