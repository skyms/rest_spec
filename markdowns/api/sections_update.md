# Update the properties of sections object.

Update the properties of sections object.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
PATCH /users/<objectId>/notes/sectionGroups/<id>
PATCH /drive/root/createdByUser/notes/sectionGroups/<id>
PATCH /drive/root/lastModifiedByUser/notes/sectionGroups/<id>
```
### Optional request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply the values for relevant fields that should be updated. Existing properties that are not included in the request body will maintain their previous values or be recalculated based on changes to other property values. For best performance you shouldn't include existing values that haven't changed.

| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String||
|createdTime|DateTimeOffset||
|lastModifiedBy|String||
|lastModifiedTime|DateTimeOffset||
|name|String||
|sectionGroupsUrl|String||
|sectionsUrl|String||
|self|String||

### Response
If successful, this method returns a `200 OK` response code and updated [sections](../resources/sections.md) object in the response body.
### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "update_sections"
}-->
```http
PUT /users/<objectId>/notes/sectionGroups/<id>
Content-type: application/json
Content-length: 3

{
}
```
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.sections"
} -->
```http
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 3

{
}
```

<!-- uuid: 93713206-fa02-48df-97bb-72304b6d766e
2015-10-25 12:56:09 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Update the properties of sections object.",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->