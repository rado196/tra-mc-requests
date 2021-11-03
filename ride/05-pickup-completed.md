# pickupCompleted

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: PrrfSYrAMMLNqvoAeATLxWDzeojrydPdKqD9V0JbkSSiKEt5EeTNiDE2L3Ava6j0smalcPe4C2yxvEtws3Bn+A==
```

### Body:

```json
{
  "eventId": "14300742#1635951090#6182a1f2bf10b",
  "eventTime": "2021-11-03T14:51:30+00:00",
  "eventType": "pickupCompleted",
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
  "longitude": -118.44715171,
  "signatureURL": "https://api.therightassist.com/images/signatures/patient/6182a1f1d5266.png"
}
```
