# basic-node-express-app

basic-node-express-app is a tutorial for an express.js application.

## Installation

Use the node package manager "npm i express" to install express

```bash
npm install express
```

## Usage

```JavaScript
const express = require('express');
const app = express();
const port = port#;

app.get('/', function(req, res){
    res.sendFile(__dirname + '/index.html');    
});

app.listen(port, function(){
    console.log('Server is started on port port#')
});
```

