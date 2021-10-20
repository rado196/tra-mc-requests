# Check Access Token

### Request:
```
GET: {{app_host}}/api/insurance/modivcare/check-access-token
```

### Headers:
```http
Cache-Control: no-cache
User-Agent: PostmanRuntime/7.28.4
Host: api.therightassist.com
Connection: keep-alive
Accept: */*
Authorization: Bearer <ACCESS_TOKEN>
```

### Success response example:
```json
{
  "status": "valid"
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
  - Authorization header is required.
  - Only Bearer tokens was accepted.
  - Access token is invalid.
  - Access token expired.
  - Access to this API was disabled for you. 
