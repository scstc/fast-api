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
|true|apiId|String|copy1695282284993d73018||


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
  "timestamp": 1702605991286,
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
      "children": [
        {
          "name": "BondKey",
          "description": "BondKey",
          "children": []
        },
        {
          "name": "BeginHoldAmt",
          "description": "BeginHoldAmt",
          "children": []
        },
        {
          "name": "EndHoldAmt",
          "description": "EndHoldAmt",
          "children": []
        },
        {
          "name": "EndCostAmt",
          "description": "EndCostAmt",
          "children": []
        },
        {
          "name": "EndMarketValue",
          "description": "EndMarketValue",
          "children": []
        },
        {
          "name": "CleanMarketValue",
          "description": "CleanMarketValue",
          "children": []
        },
        {
          "name": "FloatProfitLoss",
          "description": "FloatProfitLoss",
          "children": []
        },
        {
          "name": "Nominal",
          "description": "Nominal",
          "children": []
        },
        {
          "name": "Turnover",
          "description": "Turnover",
          "children": []
        },
        {
          "name": "DV01",
          "description": "DV01",
          "children": []
        },
        {
          "name": "BondCreditRate",
          "description": "BondCreditRate",
          "children": []
        },
        {
          "name": "RemainingYear",
          "description": "RemainingYear",
          "children": []
        },
        {
          "name": "TermTypeName",
          "description": "TermTypeName",
          "children": []
        },
        {
          "name": "CpnRate",
          "description": "CpnRate",
          "children": []
        },
        {
          "name": "BondName",
          "description": "BondName",
          "children": []
        },
        {
          "name": "BondType",
          "description": "BondType",
          "children": []
        },
        {
          "name": "Province",
          "description": "Province",
          "children": []
        },
        {
          "name": "IssuerName",
          "description": "IssuerName",
          "children": []
        },
        {
          "name": "BondOptionYear",
          "description": "BondOptionYear",
          "children": []
        },
        {
          "name": "HoldRatio",
          "description": "HoldRatio",
          "children": []
        },
        {
          "name": "TurnoverRatio",
          "description": "TurnoverRatio",
          "children": []
        },
        {
          "name": "ChgHoldAmt",
          "description": "ChgHoldAmt",
          "children": []
        },
        {
          "name": "TermStructure",
          "description": "TermStructure",
          "children": []
        },
        {
          "name": "Industrygics2",
          "description": "Industrygics2",
          "children": []
        }
      ]
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


