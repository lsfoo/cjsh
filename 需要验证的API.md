+++
Categories = ["Other"]
Tags = ["cj"]
date = "2017-06-11T09:59:38+08:00"
title = "需要验证token的API列表-用户版"

+++
###### -
#### 获取用户信息
>/Api/Android/getuserinfo.aspx?userid=30479

#### 我的消息列表
>/Api/Android/GetPushList.aspx?pageindex=1&userid=30479&usertype=1

#### 服装订单
>/Api/Commodity/GetCommodityOrderListForUser.aspx?pagesize=12&pageindex=1&state=2&paystate=0&userid=30479

#### 确认收货
>/Api/Commodity/UserConfirmReceipt.aspx?orderid=17051715020434485045&orderunid=33&userid=30479

#### 服装订单收货信息
>/Api/Commodity/GetCommodityOrderDetail.aspx?unid=39

#### 我的订单礼品订单
>/Api/Android/getuserinfo.aspx?userid=30479

#### 礼品订单详情
>/Api/Android/GetIntegralDetail.aspx?id=39012&isios=1

####  我的积分列表
>/Api/Android/pointrecordlist.aspx?userid=30479&pagesize=30&pageindex=1

#### 密码重置
>/Api/Android/ResetPassword.aspx?userid=30479&newpassword=123456&oldpassword=123456

#### 我的收藏
>/Api/Android/GetUserCollectShop.aspx?pagesize=20&pageindex=1&userid=30479

#### 地址列表
>/Api/Android/GetUserAddressList.aspx?userid=30479&pagesize=100&pageindex=1

#### 编辑地址信息
>/Api/Android/SaveUserAddress.aspx?receiver=张三11&address=宏利大道&streetaddress=亿隆如意家园&mobilephone=15136238704&userid=30479&dataid=29871&lng=114.674717&lat=35.192325&op=0

#### 删除地址信息
>/Api/Android/SaveUserAddress.aspx?receiver=张三11&address=宏利大道&streetaddress=亿隆如意家园&mobilephone=15136238704&userid=30479&dataid=29871&lng=114.674717&lat=35.192325&op=-1

#### 添加地址信息
>/Api/Android/SaveUserAddress.aspx?receiver=yang&address=guojiahcneng&streetaddress=yilong &mobilephone=18134413448&userid=30479&dataid=1&lng=35.199013&lat=114.675170&op=1



##首页

### 收藏店铺
>/Api/Android/SaveCollection.aspx?userid=30479&op=1&togoid=4577

#### 外卖提交订单
>/Api/Android/SubmitOrder.aspx

#### 获取外卖订单支付编号
>/Api/Android/buildpaynum.aspx?price=15.0&orderid=17061017205534489340

#### 提交店内付订单
>/Api/Android/SubmitInStorePayOrder.aspx

#### 获取店内付订单支付编号
>/Api/Android/BuildInStorePayNum.aspx?price=1.00&orderid=17061017225934486991

#### 提交店内买单评价
>/Api/Android/EditPayStoreComment.aspx


## 积分
#### 积分兑换接口
>/Api/Android/changegift.aspx


## 订单
#### 外卖订单列表
>/Api/Android/getorderlistbyuserid.aspx?userid=30479&pagesize=20&pageindex=1

#### 待评价订单列表
>/Api/Android/GetNeedReviewOrderList.aspx?userid=30479&pagesize=20&pageindex=1

#### 外卖订单详情
>/Api/Android/GetOrderDetailByOrderId.aspx?orderid=17042218202923653153&ordertype=1

#### 订单状态
>/Api/Android/GetDeliverLocationByOrderID.aspx?orderid=17042218202923653153

#### 提交外卖评价
>/Api/Android/submitreview.aspx

## 服装

#### 添加购物车
>/App/Commodity/AddShoppingCarCommodity.aspx


#### 获取购物车列表
>/App/Commodity/GetShoppingCarList.aspx

#### 编辑购物车
>/App/Commodity/EditShoppingCarCommodityNum.aspx

#### 提交订单
>/App/Commodity/SubmitCommodityOrder.aspx

#### 订单列表
>/App/Commodity/GetCommodityOrderListForUser.aspx
