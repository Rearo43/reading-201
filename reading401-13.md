# Bearer Authorization

Write the following steps in the correct order:
Receive access token
Redirect to a third party authentication endpoint
Register your application to get a client_id and client_secret
Make a request to a third-party API endpoint
Ask the client if they want to sign in via a third party
Receive authorization code
Make a request to the access token endpoint
What can you do with an authorization code?
#### What can you do with an access token?
  > You can make API requests, and use them to keep track of how many times or who it using your site/ code.
#### What’s a benefit of using OAuth instead of your own basic authentication?
  > Because the code is already written and someone else has dedicated a lot of time to make it secure.


### Term
- Client ID: public identifier for apps
- Client Secret: secret known only to the application and the authorization server
- Authentication Endpoint: used by the client to obtain authorization from the resource owner via user-agent redirection
- Access Token Endpoint: used by the client to exchange an authorization grant for an access token, typically with client authentication
- API Endpoint: used to pinpoint specific info from an API
- Authorization Code: obtained by using an authorization server as an intermediary between the client and resource owner
- Access Token: a string denoting a specific scope, lifetime, and other access attributes
