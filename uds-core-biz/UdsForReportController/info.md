# info

> URL: http://localhost:8181/uds/report/api/info
>
> Origin Url: http://localhost:8181/uds/report/api/info
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|appKey|reportcenter|

### Parameters

##### Path parameters

| Parameter | Type | Value | Description |
|---------|------|------|------------|


##### URL parameters

|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Body parameters

###### JSON

```

```

###### JSON document

```
null
```


##### Form URL-Encoded
|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|
|true|apiId|String|daf6f82616c44f408b57cbb75304cafe||


##### Multipart
|Required | Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


### Response

##### Response example

```
{
  "success": true,
  "code": 200,
  "message": "success",
  "timestamp": 1702605938805,
  "data": [
    {
      "name": "success",
      "description": "success",
      "children": []
    },
    {
      "name": "code",
      "description": "code",
      "children": []
    },
    {
      "name": "message",
      "description": "message",
      "children": []
    },
    {
      "name": "timestamp",
      "description": "timestamp",
      "children": []
    },
    {
      "name": "data",
      "description": "data",
      "children": []
    }
  ]
}
```

##### Response document
```
{
	"code":"返回代码",
	"data":{},
	"success":"成功标志",
	"message":"消息",
	"timestamp":"时间戳"
}
```


