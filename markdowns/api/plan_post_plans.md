# Create Plan

Use this API to create a new Plan.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /plans

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP header. Update accordingly...|

### Request body
In the request body, supply a JSON representation of [Plan](../resources/plan.md) object.


### Response
If successful, this method returns `201, Created` response code and [Plan](../resources/plan.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_plan_from_plans"
}-->
```http
POST /plans
Content-type: application/json
```
In the request body, supply a JSON representation of [Plan](../resources/plan.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "plan"
} -->
```json
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 179
{
  "createdBy": "createdBy-value",
  "owner": "owner-value",
  "title": "title-value",
  "totalTasks": 99,
  "activeTasks": 99,
  "id": "id-value",
  "version": "version-value"
}
```

<!-- uuid: e2f95b9f-81be-40f3-8895-a65f15f9187c
2015-10-16 09:51:14 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create Plan",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->