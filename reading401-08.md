# Express Routing & Connected API
> Routes can be managed in separate modules from the main server, allowing us to extract that logic and wiring to be more topical.


### How does this change the server's role?


#### Index.js - Entry Point
  - How apps take in a users (clients) request and respond
  - End points refer to what you see at the end of a URL
  - Methods like GET DELETE POST and more (app.use for middleware)
#### Server.js - Hub, Exported Server
  > House routes (move to multiple files by sections later to keep modular)

#### Models/categories.js, etc - Data Models
  > A data model is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities

#### Routes/categories.js, etc - Routers and Handlers
  > Use the express.Router class to create modular, mountable route handlers. A Router instance is a complete middleware and routing system; for this reason, it is often referred to as a “mini-app”.
    #### Sample code
    > Using express.Router to enable the app to handle requests to (for this example) /birds and /birds/about
    var express = require('express')
      var router = express.Router()

        // middleware that is specific to this router
        router.use(function timeLog (req, res, next) {
          console.log('Time: ', Date.now())
          next()
        })
        // define the home page route
        router.get('/', function (req, res) {
          res.send('Birds home page')
        })
        // define the about route
        router.get('/about', function (req, res) {
          res.send('About birds')
        })

        module.exports = router
          |       |       |
          v       v       v
        var birds = require('./birds')
        app.use('/birds', birds)

#### Sample app verbal breakdown 
  - Basic Routes: Home, About
  - Route Middleware to log requests to the console
  - Route with Parameters
  - Route Middleware for Parameters to validate specific parameters
  - Login routes Doing a GET and POST on /login
  
  #### Sample code
    app.get('/sample', function(req, res) {
      res.send('this is a sample!'); 
    });
    
    or -------- Both do the same thing the one below allows for better orginization and allowing the 
    routes to all be at the top so devs can easily see what the file holds.
    
    app.get('/sample', sampleF);
    
    function sampleF(req, res) {
      res.send('this is a sample);
    }
