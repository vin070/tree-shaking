* NodeJS has two module system
    1. CommonJS  modules
    2. ECMAScript modules 

* How to run project as ECMAScript modules
Authors can tell Node.js to interpret JavaScript as an ES module via the .mjs file extension, "type" field in the package.json with a value "module", or the --input-type flag with a value of "module". 

* How to run project as CommonJS modules
Authors can explicitly tell Node.js to interpret JavaScript as CommonJS via the .cjs file extension, the package.json "type" field with a value "commonjs", or the --input-type flag with a value of "commonjs"

When code lacks explicit markers for either module system, Node.js will inspect the source code of a module to look for ES module syntax. If such syntax is found, Node.js will run the code as an ES module; otherwise it will run the module as CommonJS. 