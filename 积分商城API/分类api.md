
### 分类页面

#### 一级

GET /Api/Mall/Category.aspx?ac=list&depth=1


#### 二级

GET /Api/Mall/Category.aspx?ac=list&depth=2&pid={{一级分类ID}}

```
{
    "banner": {
        "Src": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png",
            "Link": "www.baidu.com"

    },
        "list": [
        {
            "Id": 37,
            "Name": "休闲零食",
            "Son": [
            {
                "Id": 4,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            },
            {
                "Id": 3,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            },
            {
                "Id": 2,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            },
            {
                "Id": 1,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            }

            ]

        },
        {
            "Id": 38,
            "Name": "饼干蛋糕",
            "Son": [
            {
                "Id": 8,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            },
            {
                "Id": 7,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            },
            {
                "Id": 6,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            },
            {
                "Id": 5,
                "Name": "三级分类",
                "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

            }

            ]

        },
        {
            "Id": 39,
            "Name": "糖果巧克力",
            "Son": []

        },
        {
            "Id": 41,
            "Name": "冲调饮品",
            "Son": []

        },
        {
            "Id": 42,
            "Name": "粮油调味",
            "Son": []

        },
        {
            "Id": 104,
            "Name": "名人堂",
            "Son": []

        }

    ]

}
```

