## Tue, 13 Jun 2017 15:40:04 +0800
>test.cjshenghuo.com
### 注册

>POST /Api/Customer/join.aspx

|  字段          |        说明        |
| -------------  | ------------------ |
|   Tel          | 用户已存在 |
|   Password     | 给true或者false    |
|   IsNeedPromoter | 是否需要推荐人第一次请求IsNeedPromoter=1|
|   PromoterTel    | 推荐人电话                       |

返回信息

|   state        |        内容        |
| -------------  | ------------------ |
|   -3   | 用户已存在                 |
|   -1   | 推荐人不存在               |
|   0    | 推荐人没有开能推荐功能     |
|   1    | 成功                       |

![](https://github.com/lsfoo/cjsh/blob/master/images/%E6%96%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E5%9B%BE.png)

### 设置用户是否为推荐人

>POST /Api/Customer/PromoterSet.aspx

|  字段          |        说明        |
| -------------  | ------------------ |
|   userId       |       |
|   isPromoter   | 给true或者false    |

返回

|返回值|内容|
|---|---|
|1|更新更成功|
|0|userid不存在|

### 推荐中心页面接口

>GET /Api/Customer/Promoter.aspx?user_id=30528&page=1&page_per=2

返回信息

```javascript
/*
promoteCount:   推荐总数量

totalPoint:     历史总积分

d:              数据列表
*/
{
    "promoteCount":1,
    "totalPoint":110,
    "d":[
            {
                "Time":"2017-06-15T09:19:16.28",
                "Msg":"外卖消费",
                "Point":10.00
            }
         ]
}
```

