1. Create a Folder
2. npm init (install default package.json)
3. npm install express mongoose morgan helmet dotenv nodemon
4. Create index.js (main file)
    const express = require("express");

    app.listen(8200, () => {
      console.log("app is running on " + 8200);
    });
5. change scripts in pakage.json 
"scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
   },
7. npm run dev
8. 
