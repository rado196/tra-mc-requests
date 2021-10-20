# Cancel Ride

### Request:
```
POST: {{app_host}}/api/insurance/modivcare/{{tp_id}}/ride/{{id}}/cancel
```

### Headers:
```http
Cache-Control: no-cache
User-Agent: PostmanRuntime/7.28.4
Host: api.therightassist.com
Connection: keep-alive
Accept: */*
Accept-Encoding: gzip, deflate, br
Authorization: Bearer <ACCESS_TOKEN>
Content-Type: application/json
Content-Length: <AUTO_GENERATED>
```

### Body:
```json
{
  "id": "<RIDE_ID>",
  "transportationProviderId": "{{tp_id}}"
}
```

### Success response example:
```json
{
  "status": "OK"
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
  - _`Authorization header is required.`_
  - _`Only Bearer tokens was accepted.`_
  - _`Access token is invalid.`_
  - _`Access token expired.`_
  - _`Access to this API was disabled for you.`_
  - No ride found with provided ID.
