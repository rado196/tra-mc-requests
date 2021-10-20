# OAuth Login

### Request:
```
POST: {{app_host}}/api/insurance/modivcare/oauth2/token
```

### Headers:
```http
Cache-Control: no-cache
User-Agent: PostmanRuntime/7.28.4
Host: api.therightassist.com
Connection: keep-alive
Accept: */*
Accept-Encoding: gzip, deflate, br
Content-Type: application/json
Content-Length: <AUTO_GENERATED>
```

### Body:
```json
{
  "client_id": "traci_Wdv5oGUIJpjNaXwMuz12EfPYmq",
  "client_secret": "tracs_AL5DTggH6KbuPr1cP0d9M1VQgKarCEZNeLqs85DJIp24ak5ID8HmR7dbCP",
  "grant_type": "client_credentials"
}
```

### Success response example:
```json
{
  "token_type": "Bearer",
  "access_token": "<ACCESS_TOKEN>",
  "expires_in": 2422800,
  "scope": ""
}
```

### Failure response example:
```json
{
  "status": "error",
  "message": "<ERROR_MESSAGE>",
}
```

`ERROR_MESSAGE`:
  - Invalid grant_type (only "client_credentials" is allowed).
  - Incorrect client_id or client_secret.
  - Your client_id was disabled.
