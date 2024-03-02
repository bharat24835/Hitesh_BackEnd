## Chai Or Backend Series

This is Video Series on BackEnd with JS
-[Models Link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj)

## Basic Ideas
- Hitesh Used Module based Importing
- In JavaScript , import is done in 2 ways<br>
  1- Common JS (require syntax) <Br>
  2- Module (import syntax)

  Q- How to do Module Based Importing?<br>
     Just Introduce { "type" :"module" }  in package.json

- WhenEver a file is modified (or updated), Nodemon restart the server <br>
   1 - npm install --save-dev nodemon<br>
   2-  Introduce in package.json <br> "scripts": { <br>
          "dev": "nodemon src/index.js"<br>
        },<br>
  