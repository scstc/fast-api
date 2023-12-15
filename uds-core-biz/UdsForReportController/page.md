# page

> URL: http://localhost:8181/uds/report/api/page
>
> Origin Url: http://localhost:8181/uds/report/api/page
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
|false|apiId|String|apiId_mv4vn|appId|
|false|keywords|String|keywords_3nj7y|关键词|
|false|apiName|String|apiName_aonnr|接口名称|
|false|apiGroupId|String|apiGroupId_pf0xr|分组id|
|false|groupParentFlag|Boolean|true|是否父亲节点|
|false|dataSourceKey|String|dataSourceKey_o22j2|数据源|
|false|apiType|String|apiType_iejsl|接口类型  SQL,WEB_IDE,SPL|
|false|apiStatus|String|apiStatus_m0fa8|状态  0 未上线  1  已经上线|
|false|apiIds|String|apiIds_ogr7j|apiIds|
|true|pageNumber|Number|1|当前页|
|true|pageSize|Number|10|每页数目|
|false|sort|String|sort_2w5to||
|false|order|String|order_l57l9||
|false|notConvert|Boolean|true||


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
  "timestamp": 1702605873740,
  "data": {
    "records": [
      {
        "apiId": "daf6f82616c44f408b57cbb75304cafe",
        "apiName": "getDeptPortfolioNos",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "d9d34db9c3ab4d3791edede00616dc4c",
        "apiName": "sendZoneAbroadPositionData",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "copy1695806381185d18741",
        "apiName": "getCalendarMap",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "29c77858923841bea654fc4e48a81d7b",
        "apiName": "excel转换json数据",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "d951209dff804475ac3894ffa5c7819d",
        "apiName": "组合指标汇总",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "88161a52fee64e35afe953bee3735593",
        "apiName": "getAllProdList",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "copy1695605513297d54783",
        "apiName": "getTopFiveBondTrades",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "429032f8ba7146179ee31c4ad7cfc36f",
        "apiName": "资金存量分析汇总",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "copy1695282284993d73018",
        "apiName": "getTopTenBondPositions",
        "dataSourceKey": "WEB_IDE"
      },
      {
        "apiId": "0b6ce8d8530e468ea02b4f5b67b4b286",
        "apiName": "组合持仓概览",
        "dataSourceKey": "WEB_IDE"
      }
    ],
    "total": 42,
    "size": 10,
    "current": 1,
    "orders": [],
    "optimizeCountSql": true,
    "searchCount": true,
    "countId": null,
    "maxLimit": null,
    "pages": 5
  }
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


