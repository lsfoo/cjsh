

GET /Api/Mall/List.aspx?ac=gifts&page=1&page_per=10&sort=price&desc=1&c1=0&c2=0&c3=2&brand=1&top=1&rec=1&s=%E5%88%86

| 参数          | 描述                                                 | 类型    |
| ------------- | :-------------:                                      | :-----: |
| ac            | gifts=积分产品列表, shop=商家列表                    | string  |
| page          | 第几页                                               | int     |
| page_per      | 每页数量                                             | int     |
| sort          | 价格price 积分point 指定sortnum 销量salenum 库存sock | string  |
| desc          | 1倒序   0正序                                        | int     |
| c1            | 一级分类id                                           | int     |
| c2            | 二级分类id                                           | int     |
| c3            | 三级分类id                                           | int     |
| brand         | 品牌id                                               | int     |
| top           | 筛选置顶 top=1 显示置顶数据                          | int     |
| rec           | 筛选推荐   rec=1 显示推荐数据                        | int     |
| s             | 搜索内容                                             | string  |
| shop_id       | 商家ID                                               | int     |


不需要要参数可以不请求,或者按类型给0或者空

```
{
    "list": [
    {
        "Id": 5198,
            "Name": "积分超多",
            "BrandId": 1,
            "Brand": "22222",
            "ShopId": 916,
            "Shop": "张英红焖鸭",
            "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201705/201705301603542929.jpg",
            "BigPic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201705/201705301603542929.jpg",
            "Ctx": "&nbsp;",
            "C1Id": 1033,
            "C1": "商超百货",
            "C2Id": 37,
            "C2": "休闲零食",
            "C3Id": 2,
            "C3": "三级分类",
            "Stock": 45,
            "Price": 5005.0,
            "Point": 5005,
            "SaleNum": 0,
            "Top": true,
            "REC": true

    },
    {
        "Id": 5197,
        "Name": "积分多多",
        "BrandId": 1,
        "Brand": "22222",
        "ShopId": 916,
        "Shop": "张英红焖鸭",
        "Pic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201705/201705301603169960.jpg",
        "BigPic": "http://ftj0paqjf6lyxulz.cjshenghuo.com/upload/201705/201705301603169960.jpg",
        "Ctx": "&nbsp;",
        "C1Id": 1033,
        "C1": "商超百货",
        "C2Id": 37,
        "C2": "休闲零食",
        "C3Id": 2,
        "C3": "三级分类",
        "Stock": 10,
        "Price": 2003.0,
        "Point": 2003,
        "SaleNum": 0,
        "Top": true,
        "REC": true

    }

    ]

}
```
