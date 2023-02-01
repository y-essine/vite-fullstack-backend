# MEVN fullstack app backend
This is the server for the MEVN fullstack app. 

[Frontend repository (Vue)](https://github.com/y-essine/vite-fullstack/)

## Config
As seen in the config.js file `mongoUri: process.env.MONGO_URI,`, the database uri is access through the environment variables so in order to set it up 
use the cmd `export MONGO_URI=<your_uri>` replacing your_uri with yours or you can create .env file and put it there...

## Running the server
Run in dev (nodemon) :
```
npm run dev
```

Prod command:
```
npm run start
```
