Node jS :-


- JS runtime enviroment.
- It is used for server side programming.
- Node.js is not a language , library or framework.


## Package.json :-

 - package.json is a file in a Node.js Project that stores metadata about the project.
  (npm init)
 - {
  "name": "hello-world",
  "version": "1.0.0",
  "description": "Node jS :-",
  "license": "ISC",
  "author": "",
  "type": "commonjs",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  }
}


=> name :- "The name of the project",
=> version :- current version of the project.
=> description :- A breif description of yoour project.
=> main :- The main entry point of your project.
=> script :- Define shortcuts for common tasks . Like start for running aa project(e.g: the main javascript file.)
=> author :- The author / creator of the project.
=> license :- The license under which the project is released.

## module.exports (requiring files) :-

- require()  :- a built-in function to include external modules exist in seprate files.
- module .exports :- is a sepcial object