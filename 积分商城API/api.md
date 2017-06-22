
### 分类页面

#### 一级

GET /Api/Mall/Category.aspx?ac=list&depth=1

#### 二级

GET /Api/Mall/Category.aspx?ac=list&depth=2&pid={{一级分类ID}}

```
[
{
    "Id": 37,
        "Name": "休闲零食",
        "Sort": 0,
        "Son": [
        {
            "Id": 4,
            "Name": "三级分类",
            "Sort": 4,
            "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

        },
        {
            "Id": 3,
            "Name": "三级分类",
            "Sort": 3,
            "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

        },
        {
            "Id": 2,
            "Name": "三级分类",
            "Sort": 2,
            "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

        },
        {
            "Id": 1,
            "Name": "三级分类",
            "Sort": 1,
            "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

        }

    ]

},
{
    "Id": 38,
    "Name": "饼干蛋糕",
    "Sort": 0,
    "Son": [
    {
        "Id": 8,
        "Name": "三级分类",
        "Sort": 8,
        "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

    },
    {
        "Id": 7,
        "Name": "三级分类",
        "Sort": 7,
        "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

    },
    {
        "Id": 6,
        "Name": "三级分类",
        "Sort": 6,
        "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

    },
    {
        "Id": 5,
        "Name": "三级分类",
        "Sort": 5,
        "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201703/201703270321043764.png"

    }

    ]

},
{
    "Id": 39,
    "Name": "糖果巧克力",
    "Sort": 0,
    "Son": []

},
{
    "Id": 41,
    "Name": "冲调饮品",
    "Sort": 0,
    "Son": []

},
{
    "Id": 42,
    "Name": "粮油调味",
    "Sort": 0,
    "Son": []

},
{
    "Id": 104,
    "Name": "名人堂",
    "Sort": 0,
    "Son": []

}

]
```
