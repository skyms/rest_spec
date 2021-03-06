# Get EventMessageRequest

Retrieve the properties and relationships of eventmessagerequest object.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http

```
### Optional query parameters
This method supports the [OData Query Parameters](http://graph.microsoft.io/docs/overview/query_parameters) to help customize the response.

### Request headers
| Name      |Description|
|:----------|:----------|
| Authorization  | Bearer <code>|
| Workbook-Session-Id  | Workbook session Id that determines if changes are persisted or not. Optional.|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and [EventMessageRequest](../resources/eventmessagerequest.md) object in the response body.
### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "get_eventmessagerequest"
}-->
```http

```
##### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.EventMessageRequest"
} -->
```http
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 938

{
  "PreviousLocation": {
    "DisplayName": "DisplayName-value",
    "LocationEmailAddress": "LocationEmailAddress-value",
    "Address": {
      "Type": "Type-value",
      "PostOfficeBox": "PostOfficeBox-value",
      "Street": "Street-value",
      "City": "City-value",
      "State": "State-value",
      "CountryOrRegion": "CountryOrRegion-value",
      "PostalCode": "PostalCode-value"
    },
    "Coordinates": {
      "Altitude": 99,
      "Latitude": 99,
      "Longitude": 99,
      "Accuracy": 99,
      "AltitudeAccuracy": 99
    },
    "LocationUri": "LocationUri-value"
  },
  "PreviousStartDateTime": {
    "DateTime": {
    },
    "TimeZone": "TimeZone-value"
  },
  "PreviousEndDateTime": {
    "DateTime": {
    },
    "TimeZone": "TimeZone-value"
  },
  "ResponseRequested": true,
  "MeetingMessageType": "MeetingMessageType-value",
  "StartDateTime": {
    "DateTime": {
    },
    "TimeZone": "TimeZone-value"
  }
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Get EventMessageRequest",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->