# Create Task

Use this API to create a new Task.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /tasks

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP header. Update accordingly...|

### Request body
In the request body, supply a JSON representation of [Task](../resources/task.md) object.


### Response
If successful, this method returns `201, Created` response code and [Task](../resources/task.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_task_from_tasks"
}-->
```http
POST /tasks
Content-type: application/json
```
In the request body, supply a JSON representation of [Task](../resources/task.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "task"
} -->
```json
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 641
{
  "createdBy": "createdBy-value",
  "assignedTo": "assignedTo-value",
  "planId": "planId-value",
  "bucketId": "bucketId-value",
  "title": "title-value",
  "orderHint": "orderHint-value",
  "assigneePriority": "assigneePriority-value",
  "percentComplete": 99,
  "startDate": "datetime-value",
  "assignedToDate": "datetime-value",
  "createdDate": "datetime-value",
  "assignedBy": "assignedBy-value",
  "dueDate": "datetime-value",
  "hasNotes": true,
  "previewType": "previewType-value",
  "completedDate": "datetime-value",
  "numberOfReferences": 99,
  "appliedCategories": {
  },
  "id": "id-value",
  "version": "version-value"
}
```

<!-- uuid: efc7299b-96e2-4f3a-b732-0b86e68a779b
2015-10-16 09:51:19 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create Task",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->