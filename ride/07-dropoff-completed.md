# dropoffCompleted

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: PnOqjmCOZS+dPt5TFSn6P+7EtRn5vkevQXxA9w+ksLeD7klP6uJ4jXHObgwx0LFoET53ubPxq7/wLQ/J7MW+UA==
```

### Body:

```json
{
  "eventId": "14300742#1635951117#6182a20d9dbdb",
  "eventTime": "2021-11-03T14:51:57+00:00",
  "eventType": "dropoffCompleted",
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
