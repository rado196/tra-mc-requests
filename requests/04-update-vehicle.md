# Update Vehicle

### Request:
```
PUT: {{app_host}}/api/insurance/modivcare/{{tp_id}}/vehicles/{{id}}
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
  "id": "NWmAP83YasAExJnRAHR7FR",
  "transportationProviderId": "{{tp_id}}",
  "name": "394893",
  "make": "Honda",
  "model": "Accord",
  "color": "Blue",
  "year": "2006",
  "vin": "1FADP5AUXFL121000",
  "licensePlate": "647WEL",
  "licensePlateState": "MA",
  "credentialingStatus": "credentialed",
  "webhookURL": "https://uat-api.circulation.care/transit/webhook/atm"
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
  - No vehicle found with provided ID.
