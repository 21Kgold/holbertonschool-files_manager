# Files manager
This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

## Description

* How to create an API with Express
* How to authenticate a user
* How to store data in MongoDB
* How to store temporary data in Redis
* How to setup and use a background worker

## Setup
Ubuntu OS
```
$ lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 18.04.6 LTS
Release:        18.04
Codename:       bionic
```

Install NodeJS 12.11.x
```
$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
$ sudo bash nodesource_setup.sh
$ sudo apt install nodejs -y

$ nodejs -v
v12.22.12
$ npm -v
6.14.16
```

Install Jest, Babel, and ESLint in your project directory:
```
$ npm install --save-dev jest
$ npm install --save-dev babel-jest @babel/core @babel/preset-env
$ npm install --save-dev eslint
```

Include the configuration files:
* [package.json](./package.json)
* [babel.config.js](./babel.config.js)
* [.eslintrc.js](./.eslintrc.js)

Finally, run `npm install` from the terminal of your project folder to install all necessary project dependencies.
---

### [0. Redis utils](./utils/redis.js)
### [1. MongoDB utils](./utils/db.js)
### [2. First API](./server.js)
### [3. Create a new user](./routes/index.js)
### [4. Authenticate a user](./routes/index.js)
### [5. First file](./routes/index.js)
### [6. Get and list file](./routes/index.js)
### [7. File publish/unpublish](./routes/index.js)
### [8. File data](./routes/index.js)
### [9. Image Thumbnails](./controllers/FilesController.js)
