# rideScheduled

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: 3AhMDEfzCbMvQ7uTABd7ejxA5t6kkQ40fh1z1Owk65mE25FgQSe7ROzBijSBgexrT/0n1tA6Kb2G5qxMvNA7Xw==
```

### Body:

```json
{
  "eventId": "14300742#1635950912#6182a14080391",
  "eventTime": "2021-11-03T14:48:32+00:00",
  "eventType": "rideUnscheduled",
  "rideId": "YPaQfTjcIWuLUsvpKmqe",
  "transportationProviderId": "206540"
}
```
