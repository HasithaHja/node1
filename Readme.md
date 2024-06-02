# Node.js Backend Project

## Setup

1. Initialize a new Node.js project:
   npm init -y

2. Install Express.js:
   npm install express

3. Create app.js with the following content:

   const express = require('express');
   const app = express();
   const port = 3000;

   app.get('/', (req, res) => {
   res.send('Hello World!');
   });

   app.listen(port, () => {
   console.log(`Example app listening at http://localhost:${port}`);
   });

4. Run the server:
   node app.js
