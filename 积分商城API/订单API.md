### 订单列表

GET /api/mall/order?page=1&page_per=10&customer_id=0&deliver_id=0&state=0&sort=Cdate&desc=1

| 参数          | 描述                                              | 类型    |
| ------------- | :-------------:                                   | :-----: |
| page          | 第几页                                            | int     |
| page_per      | 每页数量                                          | int     |
| sort          | 排序字段                                          | string  |
| desc          | 1倒序   0正序                                     | int     |
| customer_id   | 用户id                                            | int     |
| deliver_id    | 骑d                                               | int     |
| state         | （0->未审核,1->审核通过,2->审核未通过,3->已发货） | int     |

参数不需要可以不给，节约流量和资源

返回

```
{
    "List": [
    {
        "IntegralList": [
        {
            "GiftsModelPrice": {
                "IntegralList": [],
                    "DataId": 1,
                    "GiftsID": 5198,
                    "GiftsModelName": "hellow",
                    "GiftsPrice": 0.1,
                    "InUse": 1,
                    "Stock": 11,
                    "Intro": "what ever",
                    "SortNum": 11,
                    "CreatTime": null,
                    "ModifyTime": null,
                    "Creator": null,
                    "Modifier": null,
                    "Picture": "~/upload/201706/201706010946153125.png",
                    "NeedIntegral": 22,
                    "SaleType": 1
            },
                "GiftsStyleSize": {
                    "IntegralList": [],
                    "DataId": 1,
                    "GiftsID": 5198,
                    "StyleSizeName": "黑就是黑",
                    "InUse": 1,
                    "Intro": "白就是白",
                    "SortNum": 1,
                    "CreatTime": null,
                    "ModifyTime": "2017-06-27T11:44:43.757",
                    "Creator": null,
                    "Modifier": "管理员",
                    "Picture": "~/upload/201706/201706271144403496.JPG"
                },
                "Unid": 1,
                "IntegralId": 31312,
                "GiftsID": 3389,
                "GiftsPrice": 111,
                "GiftsCounts": 11,
                "GiftsNeedIntegral": 11,
                "OldPrice": 11,
                "TogoId": 11,
                "adddate": null,
                "GiftsName": "1321321",
                "SizeModel": "12312",
                "ColorStyle": "12312",
                "DeliverFee": 1231,
                "ModelID": 1,
                "StyleID": 1,
                "Picture": "~/lsfoo.jpge",
                "SaleType": 1
        }
        ],
            "IntegralId": 31312,
            "CustId": 50733,
            "PayIntegral": "6",
            "DetailId": 0,
            "Cdate": "2017-05-30T15:26:54.183",
            "State": 0,
            "GiftsId": 3389,
            "Address": "亿隆国际城一期西门",
            "Phone": "18538600191",
            "Person": "杜首举",
            "Date": "",
            "GiftName": "小鸡发夹",
            "UserName": "18538600191",
            "Remark": "1108",
            "sendpeople": null,
            "CheckTime": null,
            "ReceiveTime": null,
            "Checker": null,
            "Receiver": null,
            "DeliverState": null,
            "DeliverID": null,
            "DeliveredTime": null,
            "DistributeTime": null,
            "NeedPayIntegral": 0,
            "PayMoney": 0,
            "NeedPayMoney": 0,
            "OldTotal": 0,
            "promotionmoney": 0,
            "Commission": 0,
            "PayToShop": 0,
            "AddPoints": 0,
            "PayTime": "1900-01-01T00:00:00",
            "PayState": 0,
            "CommentState": 0,
            "PayMode": null,
            "OrderID": null,
            "DeliveryFee": null
    },
    {
        "IntegralList": [],
        "IntegralId": 31311,
        "CustId": 50705,
        "PayIntegral": "20",
        "DetailId": 0,
        "Cdate": "2017-05-29T10:33:03.277",
        "State": 0,
        "GiftsId": 5175,
        "Address": "过户基本v刚刚刚刚",
        "Phone": "15136238704",
        "Person": "wangh",
        "Date": "",
        "GiftName": "2",
        "UserName": "13253863229",
        "Remark": "",
        "sendpeople": null,
        "CheckTime": null,
        "ReceiveTime": null,
        "Checker": null,
        "Receiver": null,
        "DeliverState": null,
        "DeliverID": null,
        "DeliveredTime": null,
        "DistributeTime": null,
        "NeedPayIntegral": 0,
        "PayMoney": 0,
        "NeedPayMoney": 0,
        "OldTotal": 0,
        "promotionmoney": 0,
        "Commission": 0,
        "PayToShop": 0,
        "AddPoints": 0,
        "PayTime": "1900-01-01T00:00:00",
        "PayState": 0,
        "CommentState": 0,
        "PayMode": null,
        "OrderID": null,
        "DeliveryFee": null
    }
    ]
}
```

#### 订单详情

GET /api/mall/order/item?id=31312

| 参数          | 描述            | 类型    |
| ------------- | :-------------: | :-----: |
| id            | IntegralId      | int     |
|
```
{
    "IntegralList": [
    {
        "GiftsModelPrice": {
            "IntegralList": [],
                "DataId": 1,
                "GiftsID": 5198,
                "GiftsModelName": "hellow",
                "GiftsPrice": 0.1,
                "InUse": 1,
                "Stock": 11,
                "Intro": "what ever",
                "SortNum": 11,
                "CreatTime": null,
                "ModifyTime": null,
                "Creator": null,
                "Modifier": null,
                "Picture": "~/upload/201706/201706010946153125.png",
                "NeedIntegral": 22,
                "SaleType": 1
        },
            "GiftsStyleSize": {
                "IntegralList": [],
                "DataId": 1,
                "GiftsID": 5198,
                "StyleSizeName": "黑就是黑",
                "InUse": 1,
                "Intro": "白就是白",
                "SortNum": 1,
                "CreatTime": null,
                "ModifyTime": "2017-06-27T11:44:43.757",
                "Creator": null,
                "Modifier": "管理员",
                "Picture": "~/upload/201706/201706271144403496.JPG"
            },
            "Unid": 1,
            "IntegralId": 31312,
            "GiftsID": 3389,
            "GiftsPrice": 111,
            "GiftsCounts": 11,
            "GiftsNeedIntegral": 11,
            "OldPrice": 11,
            "TogoId": 11,
            "adddate": null,
            "GiftsName": "1321321",
            "SizeModel": "12312",
            "ColorStyle": "12312",
            "DeliverFee": 1231,
            "ModelID": 1,
            "StyleID": 1,
            "Picture": "~/lsfoo.jpge",
            "SaleType": 1
    }
    ],
        "IntegralId": 31312,
        "CustId": 50733,
        "PayIntegral": "6",
        "DetailId": 0,
        "Cdate": "2017-05-30T15:26:54.183",
        "State": 0,
        "GiftsId": 3389,
        "Address": "亿隆国际城一期西门",
        "Phone": "18538600191",
        "Person": "杜首举",
        "Date": "",
        "GiftName": "小鸡发夹",
        "UserName": "18538600191",
        "Remark": "1108",
        "sendpeople": null,
        "CheckTime": null,
        "ReceiveTime": null,
        "Checker": null,
        "Receiver": null,
        "DeliverState": null,
        "DeliverID": null,
        "DeliveredTime": null,
        "DistributeTime": null,
        "NeedPayIntegral": 0,
        "PayMoney": 0,
        "NeedPayMoney": 0,
        "OldTotal": 0,
        "promotionmoney": 0,
        "Commission": 0,
        "PayToShop": 0,
        "AddPoints": 0,
        "PayTime": "1900-01-01T00:00:00",
        "PayState": 0,
        "CommentState": 0,
        "PayMode": null,
        "OrderID": null,
        "DeliveryFee": null
}
```
