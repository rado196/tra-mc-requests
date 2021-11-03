# locationReported

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: D8Ebk9GmFAbiY+j55k9EU5LlzpeRjIcoRv6i3AVgvCR/YqAYkrEU3wfH2ShyocfZIRmomJLSvYE9i7JSF4tCeA==
```

### Body:

```json
{
  "eventId": "ivQSudzKsLFeGoDyPtAp#1635956668#6182b7bc08ccc",
  "eventTime": "2021-11-03T16:24:28+00:00",
  "eventType": "locationReported",
  "transportationProviderId": "206540",
  "latitude": 34.23163385,
  "longitude": -118.44715171,
  "bearing": 0,
  "speed": 0,
  "accuracy": 0,
  "rideIds": {
    "ivQSudzKsLFeGoDyPtAp": {
      "pickupETA": 0
    }
  }
}
```
