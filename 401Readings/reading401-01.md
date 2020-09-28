# Node Ecosystem, TDD, CI/CD

### Questions
1. Running JS outside of browser enables a server to interact with databases and APIs. All this data and info can then be pushed to the front end.
2. Modules are what make up packages. This is code written by other people ready to use by any developer.
3. NPM works with open source code that any developers can use.
4. Export function from a node module

**module.exports = function (Exported) {
  console.log(Exported);
};**

**module.exports = animals (type, name) {
  this.type = type;
  this.name = name;
}**

    **const someFunction = () => {
      console.log('Exported');
    };**

    **exports.someFunction = someFunction;**

### Vocab.
- ecosystem
  > software projects developed and co-evolve
- Node.js
  > Writing JS for backend (have open source code to use)
- V8 Engine
  > C++ writen open scource engine used in Google crome
- module
  > Type of package that can be published to npm.
- package
  > Using code that other people have focused on for a particular feature (from registry)
- node package manager (npm)
  > Enables sharing of code, check to see updates (packages/ modules) package.json
- server
  > Pushes info to front end 
- environment
  > Place to write code 
- interpreter & compiler
  > Search Results
Featured snippet from the web
Interpreter translates just one statement of the program at a time into machine code. **Compiler scans the entire program and translates the whole** of it into machine code at once. An **interpreter takes very less time to analyze the source code.**
    > [Definition from this site](https://www.businessinsider.in/difference-between-compiler-and-interpreter/articleshow/69523408.cms)
