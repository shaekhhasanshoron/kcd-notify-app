# KCD Notify App

A simple golang application. It contains a api called notify where you can request message through POST request.

### API's

Request

```
URL:  <Host>/api/notify?message=<message>
METHOD: POST
BODY: n/a
```

Response:

````
RESPONSE STATUS CODE: 200 OK
RESPONSE MESSAGE : Got Notification: <requested message from query param>
````
