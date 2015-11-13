# location resource type

The **location** resource groups geographic location-related data on OneDrive into a single structure.

It is available on the location property of item resources that have an associated geographic location.

### JSON representation

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.location"
}-->
```json
{
  "altitude": 1024,
  "latitude": 1024,
  "longitude": 1024
}

```

### Properties
| Property  | Type   | Description                                                    |
|:----------|:-------|:---------------------------------------------------------------|
| altitude  | Double | The altitude (height), in feet,  above sea level for the item. |
| latitude  | Double | The latitude, in decimal, for the item.                        |
| longitude | Double | The longitude, in decimal, for the item.                       |

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "location resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->