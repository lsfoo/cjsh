
### 分类页面

#### 一级

GET /Api/Mall/Category.aspx?ac=list&depth=1


```
[{"Id":1033,"Name":"商超百货","Sort":200},{"Id":1029,"Name":"男装","Sort":199},{"Id":1032,"Name":"女装","Sort":198},{"Id":1034,"Name":"鞋靴箱包","Sort":197},{"Id":1039,"Name":"美妆日化","Sort":196},{"Id":16,"Name":"珠宝配饰","Sort":195},{"Id":11,"Name":"手机数码","Sort":194},{"Id":1036,"Name":"母婴玩具","Sort":193},{"Id":1037,"Name":"家居家装","Sort":192},{"Id":14,"Name":"家用电器","Sort":191},{"Id":1038,"Name":"家具厨具","Sort":190},{"Id":22,"Name":"汽车用品","Sort":189},{"Id":12,"Name":"电脑办公","Sort":188},{"Id":1035,"Name":"医疗保健","Sort":187},{"Id":1030,"Name":"健身器械","Sort":186},{"Id":15,"Name":"运动户外","Sort":185},{"Id":1031,"Name":"粮油干调","Sort":184}]
```

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
