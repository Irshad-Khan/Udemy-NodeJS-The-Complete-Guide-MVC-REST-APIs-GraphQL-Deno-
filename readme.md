# Creating Server

This is initial step to create new server.
- First we need to add code below

```bash
const http = require('http');

const server = http.createServer((req, res) => {
    console.log(req);
});

server.listen(30000);
```
- In above code we import http global library and create new server and stor into server variable.
- After that on server variable we call listen method and pass port number on which our application is run 
- Now run below command in terminal
    - node app.js
- After that goto browser and hit below URI
    - http://localhost:30000/
- After that come to terminal see request object in terminal

<!-- - [Project Title](#project-title)
- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license) -->
<!-- 
## Introduction

A more detailed introduction about the project, its purpose, and any background information. -->