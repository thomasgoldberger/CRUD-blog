# Setup

Setup two folder

* client
* server

CD into server - execute the following commands to init server and load packages.

``` bash
//packages we use in that project
npm i express mongoose ejs 

//allows us to automatical refresh the server 
npm i --save-dev nodemon
```

Now change the package.json

```json
{
    ...,
    "scripts": {
        "devStart": "nodemon server.js"
    }
}
```

create the server.js file

run the nodemon script with

``` bash
npm run devStart
```
