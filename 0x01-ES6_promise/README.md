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
```utils.js```
```.eslintrc.js```

### And…
Don’t forget to run $ ```npm install``` when you have the ```package.json```


###  Response Data Format
```uploadPhoto``` returns a response with the format

```
{
  status: 200,
  body: 'photo-profile-1',
}
```

```createUser``` returns a response with the format

```
{
  firstName: 'Guillaume',
  lastName: 'Salva',
}
```

### Tasks
- 0. Keep every promise you make and only make promises you can keep
- 1. Don't make a promise...if you know you can't keep it
- 2. Catch me if you can!
- 3. Handle multiple successful promises
- 4. Simple promise
- 5. Reject the promises
- 6. Handle multiple promises
- 7. Load balancer
- 8. Throw error / try catch
- 9. Throw an error
- 10. Await / Async
