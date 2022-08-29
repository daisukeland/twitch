# twitch-api
## para consumir una api ay distintos metodos
<code>
fetch
XMLHttpRequest
ajax
request
</code>
### get Access Token
```
url: https://id.twitch.tv/oauth2/token
method: POST
Content-Type: application/json

{
 client_id: String,
 client_secret: String,
 grant_type: "client_credentials",
 scope: Array
}
```
### refresh Access Token
```
url: https://id.twitch.tv/oauth2/token
method: POST
Content-Type: application/json

{
 client_id: String,
 client_secret: String,
 grant_type: "refresh_token",
 refresh_token: String
}
```
hasta aqui llega este contenido lo saque de mi proyecto de twitch

