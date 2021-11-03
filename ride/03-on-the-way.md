# onTheWay

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: 66KExilQidF2+RSrXkSnKq2koA02Q4Q2oRBtmRo2DL9OyKEO0H2ix/GFo9UfNnvfbujMRfseh1ppOypTTs4bLQ==
```

### Body:

```json
{
  "eventId": "14300742#1635951079#6182a1e7d777e",
  "eventTime": "2021-11-03T14:51:19+00:00",
  "eventType": "onTheWay",
  "rideId": "YPaQfTjcIWuLUsvpKmqe",
  "transportationProviderId": "206540",
  "vehicle": {
    "id": "wgygkxeeil",
    "vin": "1FMZK1CM1HKA17682",
    "licensePlate": "47659G2",
    "licensePlateState": null
  },
  "driver": {
    "id": "xvpldowuco",
    "firstName": "Razmik",
    "lastName": "Shahbandari",
    "licenseNumber": "Y4499142",
    "licenseState": "CA",
    "phoneNumber": "+18186065015"
  },
  "latitude": 34.23163385,
  "longitude": -118.44715171
}
```
