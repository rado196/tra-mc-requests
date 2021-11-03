# rideChanged (WillCall)

### Request:

```
POST: {{app_host}}/transit/webhook/atms/
```

### Headers:

```http
Authorization: Bearer ffKxhdXcGMpWqb2dnKGMgFqNJFWViS
X-ATMS-Signature: FuLdXuwksqkJaM/9evlm2g+00i5nN2IEp191S1TUvkUmytHJ/o1HkMNcrWhTz+NUlcCbqHzM2qxx4VXQeM+OaQ==
```

### Body:

```json
{
  "eventId": "14300742#1635969726#6182eabeef3fd",
  "eventTime": "2021-11-03T20:02:06+00:00",
  "eventType": "rideChanged",
  "rideId": "YPaQfTjcIWuLUsvpKmqe",
  "transportationProviderId": "206540",
  "scheduledPickupTime": "2021-11-03T12:58:00+00:00"
}
```
