# Create Driver

### Request:
```
POST: {{app_host}}/api/insurance/modivcare/{{tp_id}}/drivers
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
  "id": "5XnvSGjgcDw6H3zZVtrZNx",
  "transportationProviderId": "{{tp_id}}",
  "firstName": "MAX",
  "lastName": "CLAYTON",
  "phone": "655-899-0009",
  "email": "max@clayton.com",
  "licenseId": "T081782783",
  "licenseState": "OK",
  "licenseExpiration": "2011-09-30",
  "credentialingStatus": "credentialed",
  "dob": "1994-01-06"
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
  - No driver found with provided LicenseID.
