# app landingpage function

{% api-method method="get" host="https://api.nuonchic.com" path="/v1/api/main/events" %}
{% api-method-summary %}
event list
{% endapi-method-summary %}

{% api-method-description %}
앱 메인화면 하단에 이벤트 영역.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Cake successfully retrieved.
{% endapi-method-response-example-description %}

```
[
    {
        "evtId": 9,
        "name": "Valentine's Day",
        "description": "",
        "detail": "",
        "startDate": "2020-12-31T21:00:00.000+0900",
        "endDate": "2024-01-31T21:00:00.000+0900",
        "evtCtgId": 3,
        "filePath": "https://admin.nuonchic.com/images/20210112/0ab643eebec0d9f32c138ecf5d38d8514ff7c6f2",
        "srtOrd": 1,
        "evtCntTblCol": [
            {
                "evtCttId": 3,
                "evtCntCtgCd": "1",
                "filePath": "https://admin.nuonchic.com/images/20210112/395d6fac215259ca633091da7da03a93e1d2e5a5",
                "srtOrd": 1,
                "evtId": 9,
                "name": "Valentine's Day",
                "detail": "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quod aperiam deleniti neque? Quos autem ex veritatis nam tempora, mollitia ducimus, asperiores ab neque rem aliquid beatae quaerat animi, eos iste. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quod aperiam deleniti neque? Quos autem ex veritatis nam tempora, mollitia ducimus, asperiores ab neque rem aliquid beatae quaerat animi, eos iste.",
                "evtTblName": "Valentine's Day",
                "evtCttPrdMpTblCol": [
                    {
                        "evtCttId": 3,
                        "prdId": 41,
                        "prdTblName": "Dia hem panty"
                    },
                    {
                        "evtCttId": 3,
                        "prdId": 42,
                        "prdTblName": "Journee No.1 SoFree bralette"
                    },
                    {
                        "evtCttId": 3,
                        "prdId": 43,
                        "prdTblName": "Journee No.1 SoFree briefs"
                    },
                    {
                        "evtCttId": 3,
                        "prdId": 44,
                        "prdTblName": "Leaf lace bralette"
                    }
                ]
            },
            {
                "evtCttId": 4,
                "evtCntCtgCd": "1",
                "filePath": "https://admin.nuonchic.com/images/20210112/40ca5770691688b896c0c47fb9c5c5229824b029",
                "srtOrd": 2,
                "evtId": 9,
                "name": "Valentine's Day #2",
                "detail": "공군부대, 125만원 치킨먹고 환불에 별점 테러 의혹\n\n한 공군부대가 치킨 125만원 어치를 배달 주문해 먹은 뒤 전액 환불에 별점 테러까지 했다는 의혹이 불거져 누리꾼들의 공분을 사고 있다. 그러나 군 관계자는 \"사실이 아니\"라고 반박했다.\n\n지난 11일 한 온라인 커뮤니티에는 '125만원어치 치킨 먹고 한 푼 안 낸 공군부대'라는 제목의 글이 게재됐다. 이 글에는 배달 앱 리뷰와 치킨 가게 사장의 답변 내용이 담겨있다.\n\n리뷰 작성자 A씨는 해당 치킨 가게에 별점 하나를 주면서 \"별 한 개도 아깝다. 지역 배달비 2000원이라고 돼 있는데 군부대라고 현금 1000원을 달라는 것은 무슨 경우인지 모르겠다\"고 말했다.\n\n이어 \"부대가 오기 힘든 곳이라면 (추가 배달비를) 지불해야겠지만 도심 근처에 있어서 주변 가게 중 군부대라고 추가비용 받는 곳은 없다\"며 \"군부대라고 돈 더 받고 싶으면 미리 알려 달라. 1000원 때문에 잠재고객 다 잃었은 것\"이라고 불평했다.\n\n그러면서 \"저번에 단체주문했을 때도 닭가슴살만 몇십인분 줘서 결국 부대에서 항의하고 환불받은 거로 알고 있는데 이번에도 군부대라고 호구 잡는다. 절대 비추천\"이라고 덧붙였다.\n\n이에 치킨 가게 업주는 \"전화로 말씀드렸듯 배달료는 저희가 정한 경계선이 있다\"며 \"다른 업체가 얼마를 받는지는 무관하며, 기사님이 바쁜 탓에 잊으시고 말씀드리지 않아 주의하겠다고 재차 사과드렸다\"고 해명했다.\n\n이어 \"몇 달 전 주문한 순살치킨이 60마리여서 많은 양을 조리해야 했고, 4~5개 조각 구분을 잘못해 포장이 미흡했던 점은 인정한다\"며 \"죄송하다고 거듭 사과드렸고, 대신 1마리당 100g 더 채워드렸다. 또 12만원 상당 치즈볼 120개를 서비스 드렸고, 1.25리터 콜라도 36개나 드렸다\"고 강조했다.",
                "evtTblName": "Valentine's Day",
                "evtCttPrdMpTblCol": [
                    {
                        "evtCttId": 4,
                        "prdId": 33,
                        "prdTblName": "Dia mold bralette"
                    },
                    {
                        "evtCttId": 4,
                        "prdId": 34,
                        "prdTblName": " Moonflower cotton panty"
                    },
                    {
                        "evtCttId": 4,
                        "prdId": 45,
                        "prdTblName": "Leaf lace panty"
                    }
                ]
            },
            {
                "evtCttId": 5,
                "evtCntCtgCd": "1",
                "filePath": "https://admin.nuonchic.com/images/20210112/c9ab6ba47bbf000d53ccae8c5532255da9ab81ed",
                "srtOrd": 3,
                "evtId": 9,
                "name": "Valentine's Day #3",
                "detail": "\n'코스피200 변동성 지수' 7개월 만에 최고점\n개인 투자자 12일에도 2조원 넘게 순매수\n고객예탁금·신용융자잔고 역대 최고치 기록\n코스피지수가 전날보다 22.50(0.71%) 내린 3125.95에 거래를 마친 12일 오후 서울 중구 하나은행 딜링룸에서 한 딜러가 자리로 향하고 있다. 연합뉴스\n\"개인 투자자들, 지나친 흥분 상태\"..'공포지수'도 강력 경고음\n\n코스피지수가 전날보다 22.50(0.71%) 내린 3125.95에 거래를 마친 12일 오후 서울 중구 하나은행 딜링룸에서 한 딜러가 자리로 향하고 있다. 연합뉴스\n지난해 국내 주식시장 상승세를 주도했던 개인 투자자들이 새해 들어서도 대거 증시에 뛰어들고 있다. 코스피지수의 등락과 무관하게 강력한 순매수 행진을 멈추지 않고 있어 자칫 큰 후유증을 앓게 될 수 있다는 경고음이 나온다.\n\n개인 투자자들은 유가증권시장에서 지수가 떨어진 12일에도 2조3천억원 어치 주식을 순매수했다. 하루 순매수 역대 최고점을 찍은 전날(4조5천억원)을 잇는 2위 기록이다. 개인 투자자들은 올해 들어 이날까지 7거래일 동안 7, 8일 이틀을 빼고는 모두 순매수 상태였다. 기관(1조7천억원)과 외국인(6천억원)은 전날과 마찬가지로 동반 매도에 나서 지수를 22.50(0.71%) 낮은 3125.95로 끌어내렸다. 지수는 오전에 반짝 올랐을 뿐 내내 하락세였고, 한때 3% 이상 급락한 3047.56까지 떨어지기도 했다.",
                "evtTblName": "Valentine's Day",
                "evtCttPrdMpTblCol": [
                    {
                        "evtCttId": 5,
                        "prdId": 15,
                        "prdTblName": "Magnolia lace bralette"
                    },
                    {
                        "evtCttId": 5,
                        "prdId": 18,
                        "prdTblName": "Magnolia lace boxer short panty"
                    },
                    {
                        "evtCttId": 5,
                        "prdId": 20,
                        "prdTblName": "Moonflower cotton bralette"
                    }
                ]
            }
        ]
    },
    {
        "evtId": 7,
        "name": "Main2",
        "description": "Main2",
        "detail": "<p>Main2-Main3</p><figure class=\"image\"><img src=\"/images/20210111/32acb398fcb0edd2e35e9c5a2cd1c41005ea4a4d.png\"></figure><p>&nbsp;</p><figure class=\"image\"><img src=\"/images/20210111/cb78dfe0b6ad7066bcd6cfa108d60f266795b527.png\"></figure>",
        "startDate": "2021-01-07T10:57:00.000+0900",
        "endDate": "2021-03-31T10:57:00.000+0900",
        "evtCtgId": 3,
        "filePath": "https://admin.nuonchic.com/images/20210112/1fbca7924656b55912c1995c21cb4cb21b5b28d2",
        "srtOrd": 3,
        "evtCntTblCol": []
    }
]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://api.nuonchic.com" path="/v1/api/events/{evtId}" %}
{% api-method-summary %}
event detail
{% endapi-method-summary %}

{% api-method-description %}
 앱 메인화면 목록 &gt; 이벤트 상세 화면  
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="evtId" type="number" required=false %}
Event ID
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



