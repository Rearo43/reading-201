# Express

### Middleware
##### Video
> Functions that are invoked by Express.js touting layer before final request is made
- Do something first then pass along
- Ex: CORS, CSRF, Check if they have access to that route -> Allow user to View (Respose)
  - Function that does work to see if user is logged in (check if user has token or correct token depending  on circumstance)
  - JS using hoisting so we can declare them anywhere and they'll get brought up to top of the file
  - app.get('/', log, hello) and app.use(log)
  
  
  
##### Reading
- Middleware functions can perform the following tasks:

  - Execute any code.
  
  - Make changes to the request and the response objects.
  
  - End the request-response cycle.
  
  - Call the next middleware function in the stack.
