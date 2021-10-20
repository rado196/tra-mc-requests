# Get Ride Events

### Request:
```
GET: {{app_host}}/api/insurance/modivcare/{{tp_id}}/ride/{{id}}/events
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
```

### Success response example _(some parts of the data will be missing depending on ride status)_:
```json
{
  "onTheWay": {
    "eventTime": "2021-09-21T09:50:45+00:00",
    "latitude": 34.205665089,
    "longitude": -118.56157842
  },
  "pickupArrived": {
    "eventTime": "2021-09-21T09:50:45+00:00",
    "latitude": 34.205665089,
    "longitude": -118.56157842
  },
  "rideCanceled": {
    "eventTime": "2021-09-21T09:50:45+00:00",
    "latitude": 34.205665089,
    "longitude": -118.56157842
  },
  "pickupCompleted": {
    "eventTime": "2021-09-21T09:50:45+00:00",
    "latitude": 34.205665089,
    "longitude": -118.56157842
  },
  "dropoffArrived": {
    "eventTime": "2021-09-21T09:50:45+00:00",
    "latitude": 34.205665089,
    "longitude": -118.56157842
  },
  "dropoffCompleted": {
    "eventTime": "2021-09-21T09:50:45+00:00",
    "latitude": 34.205665089,
    "longitude": -118.56157842
  }
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
