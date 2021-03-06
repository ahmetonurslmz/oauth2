# The OAuth 2.0 Authorization Framework
OAuth2.0 authorization server that is intermediary with client and resource owner in order to issue access token which enables client to access resource server.

## Run
Change .env.production file name to .env,</br>
Create new cluster on mongoDB and set connection url to **MONGO_URL** env variable,</br>
Add a SERVER_KEY to .env file to use it in some security verification,</br>
To run project, in the directory of project type to terminal **npm run serve**

## Process
Generate server keys,</br>
Create client and keep client id,</br></br>

**Authorization Code Grant Type:**</br>
Receive Authorization Code with client id,</br>
Issue Access Token with authorization code, client_id and 'code' grant_type.


**Password Grant Type:**</br>
Issue Access Token with random username, random password, client_id and 'token' grant_type.


## Specification
* https://tools.ietf.org/html/rfc6749
* https://tools.ietf.org/html/rfc7519
