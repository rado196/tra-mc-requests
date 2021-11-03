# rideScheduled

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: 3vzm50vCz6k6uG9wt+JH8XmjTpmkl15bdFOxyv5pKUrbFUwf0oLPRtD+2qcQN+G29e8P46TABgjsuF/NCVTZvw==
```

### Body:

```json
{
  "eventId": "14300742#1635951084#6182a1ecc1304",
  "eventTime": "2021-11-03T14:51:24+00:00",
  "eventType": "pickupArrived",
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
