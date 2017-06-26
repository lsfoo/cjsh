### 增加

POST [raw(applition/json)] /api/mall/comment


```
{
    "UserID": 2,
        "TogoID": 1,
        "GiftsID": 5175,
        "Comment": "NO ZHUANX NO DIE",
        "Grade": 5,
        "username": "luanshf",
        "GiftsCommentPicture": [
        {
            "PicturePath":"~/www.lsfoo.com"

        },
        {
            "PicturePath":"~/www.lsfoo.com"

        },
        ]

}
```
返回 评论ID

```
```

### 列表
GET api/mall/comment?page=1&page_per=2&gift_id=5175

giftid = 商品id

```
{
    "List": [
    {
        "Id": 124,
            "Comment": "NO ZHUANX NO DIE",
            "Time": "2017-06-26T16:32:40.04",
            "Name": "luanshf",
            "Grade": 5,
            "IsResponse": null,
            "Response": null,
            "ResponseTiem": null,
            "PicList": [
            {
                "Src": "http://ftj0paqjf6lyxulz.cjshenghuo.com/www.lsfoo.com"
            },
            {
                "Src": "http://ftj0paqjf6lyxulz.cjshenghuo.com/www.lsfoo.com"
            }
        ]
    }
    ]
}


```

