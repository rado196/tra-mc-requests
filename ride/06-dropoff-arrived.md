# dropoffArrived

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: w7FDyhKmicHq9XF6nwjUt6vGs7Vo4h59di1U/J27oI0ZuDGLyKVzGqB9kxxpxHtbFrWBykY93LK6TrMRA/stCg==
```

### Body:

```json
{
  "eventId": "14300742#1635951098#6182a1face5e6",
  "eventTime": "2021-11-03T14:51:38+00:00",
  "eventType": "dropoffArrived",
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
