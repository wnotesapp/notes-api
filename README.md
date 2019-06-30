# notes-api

A simple notes API built using node, express and mongoose (to connect to mongoDB).

First git clone this repo.

## Steps to run:

- You will need mongodb installed on your machine. If you have brew on a Mac, 
you can run `brew install mongodb`.
- Once you have installed mongodb, run 
  1. `mkdir -p /data/db`
  2. `sudo chown -R `id -un` /data/db`
  3. `mongod`
- After you have mongodb up and running, do a `npm install` in this repo.
- Run `node server.js`. You will get the following messages once you run this command,
  ```
  Server is listening on port 3001
  Successfully connected to the database
  ```  
