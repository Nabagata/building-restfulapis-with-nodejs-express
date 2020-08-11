# Building RESTful APIs with NodeJS and Express

## Setup the project
Clone the repository and install the node modules
``` bash
git clone https://github.com/Nabagata/building-restfulapis-with-nodejs-express.git
npm i 
```

Create .babelrc file and paste this
``` js
{
    "presets": [
        "env",
        "stage-0"
    ]
}
```

Install [MongoDB community server](https://docs.mongodb.com/manual/installation/) and start the MongoDB server by running:
``` bash
brew services start mongodb-community@4.4
```

To stop the server:
``` bash
brew services stop mongodb-community@4.4
```

Start the Node and Express server by running:
``` bash
npm start
```

[crmRoutes.js](src/routes/crmRoutes.js): Contains all the routes \
[crMModel.js](src/models/crmModel.js): Contains the CRM model \
[crmController.js](src/controllers/crmController.js): Contains all the controllers
