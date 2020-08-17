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
- Node.js
- V8 Engine
- module
  > Type of package that can be published to npm.
- package
  > Using code that other people have focused on for a particular feature (from registry)
- node package manager (npm)
  > Enables sharing of code, check to see updates (packages/ modules) package.json
- server
- environment
- interpreter
- compiler
