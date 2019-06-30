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
  
## Credits

  - [Clive Dsouza](http://github.com/clivedsouza1010)

## License

(The MIT License)

Copyright (c) 2019 Clive Dsouza

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  
