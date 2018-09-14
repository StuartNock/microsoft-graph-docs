# ResultInfo resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

The resultInfo type.

## Properties

| Property | Type   | Description          |
| :------- | :----- | :------------------  |
| code     | String | The result code.     |
| message  | String | The message.         |
| subCode  | String | The result sub-code. |

## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.resultInfo"
}-->

```json
{
  "code": "String",
  "message": "String",
  "subCode": "String"
}
```

## Example Error result

``` json
{
    "code": "100",
    "message": "Internal Server Error.",
    "subCode": "20"
}
```

## Example Generic success result

``` json
{
    "code": "200",
    "subCode": "0"
}
```

## Example Record Success result

``` json
{
    "code": "200",
    "subCode": "completedSilenceDetected"
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "resultInfo resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->