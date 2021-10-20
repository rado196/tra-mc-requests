# Update Ride

### Request:
```
PUT: {{app_host}}/api/insurance/modivcare/{{tp_id}}/ride/{{id}}
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
  "referenceId": "1-20200701-142513-A",
  "linkedRideIds": ["1-20200701-142513-B", "1-20200701-142513-C"],
  "transportationProviderId": "{{tp_id}}",
  "scheduledDate": "2020-06-22",
  "appointmentTime": "2020-09-03T18:30:00+00:00",
  "additionalPassengers": {
    "attendants": 3,
    "escorts": 1
  },
  "willCall": true,
  "billableAmount": null,
  "billableMiles": null,
  "assistanceNeeds": [],
  "billingRequired": true,
  "levelOfService": "BSTR",
  "levelOfServiceDescription": "Bariatric Stretcher",
  "levelOfServiceGroup": "Stretcher",
  "unableToSign": false,
  "signatureRequired": true,
  "additionalProperties": {
    "carseats": null,
    "member_number": "182-12-1234",
    "prior_auth_num": null
  },
  "rider": {
    "id": "2fbe1c703f6893c2bc5066fcbcaa2048",
    "firstName": "Artem",
    "middleName": "",
    "lastName": "Nykoriak",
    "dateOfBirth": "1990-01-01",
    "gender": "M",
    "weight": 200,
    "phone": "8881234567"
  },
  "pickup": {
    "address": {
      "addressLine1": "330 SW 80th St",
      "addressLine2": "",
      "city": "Oklahoma City",
      "county": "Oklahoma",
      "state": "OK",
      "zipCode": "73139",
      "latitude": 35.38615,
      "longitude": -97.518722
    },
    "scheduledTime": "2020-09-03T17:11:27.160393+00:00",
    "name": "OK CTR FOR ORTH & MULTI-SP",
    "comments": "this is what you need to know for pickup",
    "phone": {
      "number": "5555555553",
      "ext": "1"
    }
  },
  "dropoff": {
    "address": {
      "addressLine1": "331 SW 80th St",
      "addressLine2": "",
      "city": "Oklahoma City",
      "county": "Oklahoma",
      "state": "OK",
      "zipCode": "73139",
      "latitude": 35.38615,
      "longitude": -97.518722
    },
    "scheduledTime": "2020-09-03T18:19:27.160393+00:00",
    "name": "residence",
    "comments": "this is what you need to know for dropoff",
    "phone": {
      "number": "5555555553",
      "ext": "1"
    }
  },
  "webhookURL": "https://uat-api.circulation.care/transit/webhook/atms"
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
