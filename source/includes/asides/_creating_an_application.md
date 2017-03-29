## Creating an Application

In order to use the CompanyCam API, you must first have a CompanyCam
account, you can register a new application at
[https://app.companycam.com/oauth/applications](https://app.companycam.com/oauth/applications).
After successfully creating a new application, you will be given a set of 2
unique keys:

- APPLICATION ID
- APPLICATION SECRET

These keys are needed in order to obtain an access token to make the API calls.

If you are already familiar with OAuth, then all you really need to know
about are the two authentication endpoints. The authorization endpoint
and the token request endpoint.

These endpoints are:

- **/oauth/authorize**
- **/oauth/token**
