# rideScheduled

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: JNiw+TlC92pJee+OgAhN65lXjVuhBRH3G2VH3HT/O/M8eoHorAAq90DnSFgVTBCoPHhV2A88jXA2iMccGJREGg==
```

### Body:

```json
{
  "eventId": "14300742#1635951057#6182a1d1dd77b",
  "eventTime": "2021-11-03T14:50:57+00:00",
  "eventType": "rideScheduled",
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
  }
}
```
