# Product / Payment / MyPage

## Product Categories

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/codes" %}
{% api-method-summary %}
product code
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
[
    {
        "name": "BRAND A~Z",
        "prdCd": 1
    },
    {
        "name": "BRAS",
        "prdCd": 2
    },
    {
        "name": "PANTIES",
        "prdCd": 3
    },
    {
        "name": "SHAPER",
        "prdCd": 4
    },
    {
        "name": "SWLMWEAR",
        "prdCd": 5
    },
    {
        "name": "Lounge Wear",
        "prdCd": 6
    },
    {
        "name": "Night Wear",
        "prdCd": 7
    },
    {
        "name": "Nursing & Maternity",
        "prdCd": 8
    }
]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/categories/{codeId}" %}
{% api-method-summary %}
product categories
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="codeId" type="integer" required=false %}
product code ID
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
[
    {
        "fileSize": 3708119,
        "imgFilePath": "/images/20200609/cef19142c97117c38a1fc2669945fc1f54a69e27",
        "name": "Full-cup",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 2
    },
    {
        "fileSize": 0,
        "imgFilePath": "/images/ljh.png",
        "name": "T-SHIRTS",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 6
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "Wireless",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 7
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "Balconette",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 8
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "PUSH-UP",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 9
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "NURSHING&MATERNITY",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 10
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "STRAPLESS",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 11
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "LONG LINE",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 12
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "FRONT HOOK",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 13
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "CONVERTIBLE",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 14
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "SPORTS",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 15
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "BRALARRE",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 16
    },
    {
        "fileSize": 0,
        "imgFilePath": "",
        "name": "LINGERIE",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 17
    },
    {
        "fileSize": null,
        "imgFilePath": "",
        "name": "PLUNGING",
        "prdCd": 2,
        "prdCdTblName": "BRAS",
        "prdCtgId": 48
    }
]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## show bra types

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/goods/{prdCd}" %}
{% api-method-summary %}
show Product code
{% endapi-method-summary %}

{% api-method-description %}
 상품코드로 상품 조회 
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="prdCd" type="integer" required=false %}
Product Code
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name="size" type="number" required=false %}
paging size, default value 20
{% endapi-method-parameter %}

{% api-method-parameter name="page" type="number" required=false %}
current pageNumber, default value 1
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "content": [
        {
            "barCd": "8806193513967",
            "brnId": 5,
            "brnTblName": "Frenchie",
            "cost": 24.4,
            "description": " Comfort bralette totally covered with soft semidull lace of cubic effect ,Minimizing appearance of nipples even wearing without pad by applying soft 2-layer mesh net underneath the cup , With a pad pocket, you can freely insert and remove pad if you want volume, It creates a smooth back line with wide wings without hook and eye , it uses soft, elastic shoulder straps to reduce soreness. ",
            "detail": "<p>Comfort bralette totally covered with soft semidull lace of cubic effect Minimizing appearance of nipples even wearing without pad by applying soft 2-layer mesh net underneath the cup With a pad pocket, you can freely insert and remove pad if you want volume. It creates a smooth back line with wide wings without hook and eye. it uses soft, elastic shoulder straps to reduce soreness.</p><p>&nbsp;</p><figure class=\"image\"><img src=\"http://localhost:5500/images/20201016/8f5a1e89cc48a5b2c6868e890991179f43441264.png\"></figure>",
            "exposeDate": "2020-07-09T18:16:00.000+0900",
            "exposeDateLocal": "2020-07-09 18:16:00",
            "fileSize": 24544,
            "imgFilePath": "http://localhost:5500/images/20201016/75dd75cb18730661153a2b1d64b9fd4160458e7b",
            "instockDate": "2020-07-06T18:16:00.000+0900",
            "instockDateLocal": "2020-07-06 18:16:00",
            "inventoryCount": 10,
            "isDtd": false,
            "name": "Magnolia lace bralette",
            "prcId": 1,
            "prdCd": 2,
            "prdCdTblName": "BRAS",
            "prdCtgId": 16,
            "prdCtgTblName": "BRALARRE",
            "prdId": 15,
            "prdSttCd": 1,
            "prdTypCd": 1,
            "regDate": "2020-07-14T06:18:01.000+0900",
            "regDateLocal": "2020-07-14 06:18:01",
            "retailPrice": 35.0,
            "updDate": "2020-10-16T10:20:15.000+0900",
            "updDateLocal": "2020-10-16 10:20:15"
        }
    ],
    "empty": false,
    "first": true,
    "last": true,
    "number": 0,
    "numberOfElements": 9,
    "pageable": {
        "offset": 0,
        "pageNumber": 0,
        "pageSize": 20,
        "paged": true,
        "sort": {
            "empty": true,
            "sorted": false,
            "unsorted": true
        },
        "unpaged": false
    },
    "size": 20,
    "sort": {
        "empty": true,
        "sorted": false,
        "unsorted": true
    },
    "totalElements": 9,
    "totalPages": 1
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/allbrands" %}
{% api-method-summary %}
show all brands
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name="page" type="number" required=false %}
current pageNumber, default value 1
{% endapi-method-parameter %}

{% api-method-parameter name="size" type="number" required=false %}
paging size, default value 20
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/goods/{prdCd}" %}
{% api-method-summary %}
product list sorted by product code
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="prdCd" type="integer" required=false %}
product code
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name="size" type="number" required=false %}
paging size, default 20
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/designers" %}
{% api-method-summary %}
search designer
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



## write a review

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/product/{prdId}/review" %}
{% api-method-summary %}
get a review about product
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="prdId" type="number" required=true %}
 99
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer Token
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "content": [
        {
            "rvwId": 4039,
            "name": "Gorgeous Silk Bottle",
            "description": "5br9giuzj1jvfo5e6kl0g0br0ps58e7jsney450wr38sg414j5h51ep5xxq0gcrgk5cg0nqzk79zn5a9b528xm9vyfgn7daehdxulmlpi2jztv4uy1xqsd3e7t4t3t0y6ybsjhzui5us063q72ye2eftb8r331yss6",
            "rvwScore": 4,
            "regDate": "2021-01-07T12:25:10.000+0900",
            "updDate": null,
            "usrId": 7,
            "usrTblLoginId": "dbdyd@nuonchic.com",
            "rvwCtgCd": 2,
            "rvwCtgTblName": "Delivery",
            "prdId": 99
        }
    ],
    "pageable": {
        "sort": {
            "sorted": false,
            "unsorted": true,
            "empty": true
        },
        "pageNumber": 0,
        "pageSize": 20,
        "offset": 0,
        "unpaged": false,
        "paged": true
    },
    "totalPages": 1,
    "last": true,
    "totalElements": 11,
    "first": true,
    "numberOfElements": 11,
    "size": 20,
    "number": 0,
    "sort": {
        "sorted": false,
        "unsorted": true,
        "empty": true
    },
    "empty": false
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/product/{prdId}/review/new" %}
{% api-method-summary %}
write a review
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="prdId" type="number" required=true %}
product ID
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer token
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="name" type="string" required=true %}
 Gorgeous Silk Bottle
{% endapi-method-parameter %}

{% api-method-parameter name="description" type="string" required=true %}
 description comment
{% endapi-method-parameter %}

{% api-method-parameter name="rvwScore" type="number" required=true %}
1~5
{% endapi-method-parameter %}

{% api-method-parameter name="rvwCtgCd" type="number" required=true %}
2
{% endapi-method-parameter %}

{% api-method-parameter name="prdId" type="number" required=true %}
99
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "code": 100,
    "message": "ok"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="put" host="https://admin.nuonchic.com" path="/user/product/{prdId}/review/{reviewId}/modify" %}
{% api-method-summary %}
modify my review
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="prdId" type="number" required=true %}
Product ID
{% endapi-method-parameter %}

{% api-method-parameter name="reviewId" type="integer" required=true %}
Review ID
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer Token
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="prdId" type="number" required=false %}
99
{% endapi-method-parameter %}

{% api-method-parameter name="rvwId" type="string" required=true %}
4029
{% endapi-method-parameter %}

{% api-method-parameter name="name" type="string" required=false %}
Georgeous Silk Bottle
{% endapi-method-parameter %}

{% api-method-parameter name="description" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="rvwScore" type="number" required=false %}
4
{% endapi-method-parameter %}

{% api-method-parameter name="rvwCtgCd" type="number" required=false %}
1~5
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "code": 100,
    "message": "ok"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="delete" host="https://admin.nuonchic.com" path="/user/product/{prdId}review/{reviewId}/delete" %}
{% api-method-summary %}
delete my review
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="prdId" type="number" required=true %}
Product ID
{% endapi-method-parameter %}

{% api-method-parameter name="reviewId" type="number" required=true %}
Review ID
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer Token
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/mywishlist" %}
{% api-method-summary %}
wishlist
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=false %}
Bearer Token
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "content": [
        {
            "usrWshListId": 20,
            "prdId": 52,
            "usrId": 113,
            "ordCnt": 7,
            "prdTblDescription": "팬티",
            "usrTblEmail": "jermaine.schumm@gmail.com"
        }
    ],
    "pageable": {
        "sort": {
            "sorted": false,
            "unsorted": true,
            "empty": true
        },
        "pageNumber": 0,
        "pageSize": 20,
        "offset": 0,
        "unpaged": false,
        "paged": true
    },
    "totalPages": 1,
    "last": true,
    "totalElements": 2,
    "first": true,
    "numberOfElements": 2,
    "size": 20,
    "number": 0,
    "sort": {
        "sorted": false,
        "unsorted": true,
        "empty": true
    },
    "empty": false
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/mywishlist/toggle" %}
{% api-method-summary %}
wishlist toggle
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer Token
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="prdId" type="number" required=true %}
99
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

##  상품상세

{% api-method method="get" host="" path="/user/product/detail/{productId}" %}
{% api-method-summary %}
 상품코드의 상세 
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="productId" type="integer" required=true %}
 상품코
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="" path="/user/cart/create" %}
{% api-method-summary %}
장바구니 담기
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="" path="/user/pay" %}
{% api-method-summary %}
payment
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## 로그인 

{% api-method method="get" host="https://admin.nuonchic.com" path="/oauth2/authorization/facebook" %}
{% api-method-summary %}
facebook login 
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
  "token":"eyJ0eXAiOiJKdddddV1QiLCJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ0ZXN0MSIsInJvbGUiOiJyb2xlX3VzZXIiLCJ1c2VyTmFtZSI6ImthbnU5MTEiLCJleHAiOjE2MDg1NjAyMzgsInVzZXJJZCI6InRlc3QxIn0.WHf-TWI1EW9HLKYoe5b6rF2-tXL_aFpvcfMw1uhw4nEzdRUNvF4TovuBBvJl6xs4bTX9IncPf_aU8pSmRgy9iA"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/oauth2/authorization/google" %}
{% api-method-summary %}
google login
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
  "token":"eyJ0eXAiOiJKdddddV1QiLCJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ0ZXN0MSIsInJvbGUiOiJyb2xlX3VzZXIiLCJ1c2VyTmFtZSI6ImthbnU5MTEiLCJleHAiOjE2MDg1NjAyMzgsInVzZXJJZCI6InRlc3QxIn0.WHf-TWI1EW9HLKYoe5b6rF2-tXL_aFpvcfMw1uhw4nEzdRUNvF4TovuBBvJl6xs4bTX9IncPf_aU8pSmRgy9iA"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/oauth2/authorization/apple" %}
{% api-method-summary %}
apple login
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
  "token":"eyJ0eXAiOiJKdddddV1QiLCJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ0ZXN0MSIsInJvbGUiOiJyb2xlX3VzZXIiLCJ1c2VyTmFtZSI6ImthbnU5MTEiLCJleHAiOjE2MDg1NjAyMzgsInVzZXJJZCI6InRlc3QxIn0.WHf-TWI1EW9HLKYoe5b6rF2-tXL_aFpvcfMw1uhw4nEzdRUNvF4TovuBBvJl6xs4bTX9IncPf_aU8pSmRgy9iA"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/authorization/nuonchic" %}
{% api-method-summary %}
nuonchic login
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="loginId" type="string" required=false %}
loginID : email
{% endapi-method-parameter %}

{% api-method-parameter name="userpass" type="string" required=false %}
password
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "token":"eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJkYmR5ZEBudW9uY2hpYy5jb20iLCJyb2xlIjoidXNlciIsImV4cCI6MTYxMDU5NDY0OCwidXNlcklkIjo3fQ.wK6TSjraJy9F75zo6VBxdn0PTbZw9nMMiW7v2dpgXRvPjyJi-QIdtsB8zk6Swtdzf4z5OP04BxPVJA7TukPnRg"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/findpassword" %}
{% api-method-summary %}
  비밀번호 찾기
{% endapi-method-summary %}

{% api-method-description %}
 비밀번호 찾기 이후 메일로 인증번호 보내줌. 
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="email" type="string" required=true %}

{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"code": 100, "message": "ok"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/savepassword" %}
{% api-method-summary %}
 비밀번호 저장
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="oldPassword" type="string" required=false %}
old password
{% endapi-method-parameter %}

{% api-method-parameter name="newPassword" type="string" required=false %}
new password
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
  "code": 100, "message": "ok"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/policy/aboutnuonchic" %}
{% api-method-summary %}
about nuonchic
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
[
    {
        "cnt": "aboutus ",
        "id": 1,
        "ttl": "ubuntu1sdflj"
    }
]

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/policy/privacy" %}
{% api-method-summary %}
 get a privacy policy
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
[
    {
        "cnt": "<div class=\"inner_kakao_layer inner_terms_layer\"><div class=\"layer_head\"><strong class=\"tit_layer\">개인정보 수집 및 이용 동의</strong></div><div class=\"layer_body\"><div class=\"wrap_terms\"><p class=\"desc_layer\">(주)카카오는 개인정보를 안전하게 취급하는데 최선을 다합니다. <br>아래에 동의하시면 통합계정의 프로필 정보를 (주)카카오가 제공하는 카카오계정 기반의 서비스에서 편리하게 이용하실 수 있습니다. </p><p class=\"tit_desc\">[필수] 개인정보 수집 및 이용 동의</p> <table class=\"tbl_agree\"> <colgroup> <col> <col> <col> </colgroup> <thead> <tr> <th scope=\"col\">목적</th> <th scope=\"col\">항목</th> <th scope=\"col\">보유기간</th> </tr> </thead> <tbody> <tr> <td>이용자 식별 및 회원관리, 프로필 정보 연동</td> <td>이메일(아이디(*1)), 비밀번호, 이름(닉네임), 프로필사진</td> <td rowspan=\"4\">회원탈퇴 후 지체없이 삭제</td> </tr><tr> <td>친구등록 및 친구추천, 친구에게 알림 기능 제공</td> <td>친구목록</td>  </tr><tr> <td>아이디, 비밀번호 찾기 시 본인확인, 서비스와 관련된 중요사항 안내, 고객 문의 대응 등 의사소통에 이용</td> <td>연락처(이메일, 전화번호 중 최소 1개는 필수)</td>  </tr><tr> <td>인구통계학적 특성과 이용자의 관심, 기호, 성향의 추정을 통한 맞춤형 컨텐츠 추천 및 마케팅에 활용(*2)<br>서비스 부정 이용 방지</td> <td>이메일, 비밀번호, 이름(닉네임), 프로필사진, 친구목록, 연락처, 서비스 이용 내역, 서비스 내 구매 및 결제 내역</td> </tr>  </tbody> </table> <p class=\"desc_agree\">서비스 제공을 위해 필요한 최소한의 개인정보이므로 동의를 해 주셔야 서비스 이용이 가능합니다.</p><p class=\"desc_agree\">(*1) (주)카카오가 제공하는 이메일 서비스를 이용하는 경우 아이디를 수집합니다.<br>(*2) 맞춤 형 컨텐츠 추천 및 마케팅 활용 목적으로 이용자 정보와 ‘쿠키’ 또는 ‘광고식별자’기반으로 수집된 행태정보를 활용할 수 있습니다. 보다 자세한 내용 및 거부방법은 카카오 맞춤형 광고 안내 페이지(https://info.ad.daum.net/optout.do)를 확인해주세요.</p><p class=\"desc_agree\">더 자세한 내용에 대해서는 <a href=\"https://www.kakao.com/ko/privacy\" target=\"_blank\" class=\"link_agree\">카카오 개인정보처리방침</a>을 참고하시기 바랍니다.</p></div></div><div class=\"layer_foot\"><button class=\"btn_close\" type=\"button\"><span class=\"ico_account ico_close\">닫기</span></button></div></div>",
        "id": 3,
        "ttl": "개인정보취급정보"
    }
]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/policy/terms\_conditions" %}
{% api-method-summary %}
 get a terms and conditions
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
[
    {
        "cnt": "제 1 장 환영합니다, 
        "id": 2, 
        "ttl": "카카오계정 약관"
    }
]

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/registration" %}
{% api-method-summary %}
 뉴온식 회원가입
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="firstName" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="lastName" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="email" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="password" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="dateOfBirth" type="object" required=false %}
Date type
{% endapi-method-parameter %}

{% api-method-parameter name="nation" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "code": 100,
    "message": "ok"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="" %}
{% api-method-summary %}
 뉴온식 회원가입후 인증메일 발송 
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## MyPage

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/mywishlist" %}
{% api-method-summary %}
my wishlist
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer token
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "content": [
        {
            "usrWshListId": 1,
            "usrId": 7,
            "prdTblDescription": " Comfort bralette totally covered with soft semidull lace of cubic effect ,Minimizing appearance of nipples even wearing without pad by applying soft 2-layer mesh net underneath the cup , With a pad pocket, you can freely insert and remove pad if you want volume, It creates a smooth back line with wide wings without hook and eye , it uses soft, elastic shoulder straps to reduce soreness. ",
            "usrTblEmail": "nosignal95@gmail.com",
            "prdId": 15
        },
        {
            "usrWshListId": 1749,
            "usrId": 7,
            "prdTblDescription": null,
            "usrTblEmail": "nosignal95@gmail.com",
            "prdId": 2
        },
        {
            "usrWshListId": 3663,
            "usrId": 7,
            "prdTblDescription": "팬티",
            "usrTblEmail": "nosignal95@gmail.com",
            "prdId": 58
        }
    ],
    "pageable": {
        "sort": {
            "sorted": false,
            "unsorted": true,
            "empty": true
        },
        "pageSize": 20,
        "pageNumber": 0,
        "offset": 0,
        "paged": true,
        "unpaged": false
    },
    "totalPages": 1,
    "totalElements": 3,
    "last": true,
    "number": 0,
    "size": 20,
    "numberOfElements": 3,
    "sort": {
        "sorted": false,
        "unsorted": true,
        "empty": true
    },
    "first": true,
    "empty": false
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="" path="/user/mywishlist" %}
{% api-method-summary %}
add wishlist one by one
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer token
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="prdId" type="integer" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="usrId" type="integer" required=true %}

{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="delete" host="" path="/user/mywishlist/{usrWshListId}" %}
{% api-method-summary %}
delete my wishlist one by one
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="usrWshListId" type="integer" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/myorder\_history" %}
{% api-method-summary %}
 order history 
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer token
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "content": [
        {
            "fnsDate": "2020-12-18 18:32:05",
            "usrId": 7,
            "cnlDate": null,
            "ordId": 3809,
            "ordSttCd": 1,
            "ordDate": "2020-12-18 18:32:05"
        },
        {
            "fnsDate": "2020-12-18 18:32:39",
            "usrId": 7,
            "cnlDate": null,
            "ordId": 5881,
            "ordSttCd": 1,
            "ordDate": "2020-12-18 18:32:39"
        }
    ],
    "pageable": {
        "sort": {
            "sorted": false,
            "unsorted": true,
            "empty": true
        },
        "pageSize": 20,
        "pageNumber": 0,
        "offset": 0,
        "paged": true,
        "unpaged": false
    },
    "totalPages": 1,
    "totalElements": 2,
    "last": true,
    "number": 0,
    "size": 20,
    "numberOfElements": 2,
    "sort": {
        "sorted": false,
        "unsorted": true,
        "empty": true
    },
    "first": true,
    "empty": false
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/myaccount\_detail" %}
{% api-method-summary %}
my account detail
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}

{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/myaccount\_detail" %}
{% api-method-summary %}
save my account detail
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Bearer token
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://admin.nuonchic.com" path="/user/myaddressbook" %}
{% api-method-summary %}
get  my address book
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://admin.nuonchic.com" path="/user/myaddressbook" %}
{% api-method-summary %}
write a new address book
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="put" host="https://admin.nuonchic.com" path="/user/myaddressbook/{addressId}" %}
{% api-method-summary %}
modify my address book
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="addressId" type="integer" required=true %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="delete" host="https://admin.nuonchic.com" path="/user/myaddressbook/{addressId}" %}
{% api-method-summary %}
delete my address book
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="addressId" type="integer" required=true %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



