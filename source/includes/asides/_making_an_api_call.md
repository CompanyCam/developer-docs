## Making an API call

```shell
curl -X GET -H "Content-type: application/json" -H "Authorization: Bearer <ACCESS_TOKEN>" -H "X-CompanyCam-User: shawn@psych.com"
https://api.companycam.com/v2 %>/
```

The CompanyCam API is entirely JSON based. In order to make an authenticated call
to the API, you must include your access token with the call.
OAuth2 uses a BEARER token that is passed along in an Authorization
header. You should whenever possible set the `X-CompanyCam-User` HTTP header to the email address of the user performing the action. This email must match the user's email address in CompanyCam. If the `X-CompanyCam-User` header is not provided it will fallback to using the user that setup the integration.
