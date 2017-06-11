+++
Categories = ["Other"]
Tags = ["cj"]
date = "2017-06-10T14:32:03+08:00"
title = "验证API说明"

+++
###### -

### 测试地址

>http://d453400.cjshenghuo.com


### 登陆

-----------------------------------------------------------------------------

#### 用户登陆

* POST /api/login.aspx

* 参数

```
username:用户名

password:密码

client_id:客户端id

user_type:用户类型1=>用户,2=>商家,3=>骑士

device_type:设备类型
```
* 返回类型#JSON

```
auth:       success=>验证成功，failed=>验证失败

message:    002=>用户名或者密码不正确,003=>异常     

token:      用于验证

userid:     用户ID
```

* 例

```
{
    "auth":"success",
    "token":"eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0OTc2ODA4MzcuMCwidHAiOjF9.txmBYtYABG9AiPrgU6IdTqS86Yn071SkDyXTFBLhfJk",
    "userId":"6023"
}
```
-----------------------------------------------------------------------------
#### 商家登陆
* POST /api/shop/pointlogin.aspx

* 参数

```
 username:用户名

 password:密码

 client_id:客户端id
 
 user_type:用户类型1=>用户,2=>商家,3=>骑士

 device_type:设备类型
```
* 返回类型#JSON

auth:       success/failed

message:    002=>用户名或者密码不正确,003=>异常

token:      用于验证

userid:     用户ID 

state:      1=>通过审核，0=>没审核不能登陆


* 例

```

{
    "auth":"success",
    "token":"eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0OTc2ODA4MzcuMCwidHAiOjF9.txmBYtYABG9AiPrgU6IdTqS86Yn071SkDyXTFBLhfJk",
    "userId":"6023"
    "state":1
}
```
-----------------------------------------------------------------------------

### 更新token

GET /api/refreshtoken.aspx?token={token字符串}

* 返回string

```
401=token失效

403=帐号从其它设备登陆

500=没有传token

通过验证返回新的token字符串
```

* 例

```
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0OTc2ODA4MzcuMCwidHAiOjF9.txmBYtYABG9AiPrgU6IdTqS86Yn071SkDyXTFBLhfJk
```

### GET所有页面验证

* 所有GET请求添加&tk=token字符串

* 返回

* 401=token失效

* 403=帐号从其它设备登陆

* 500=没有传token

* 无错误刚正常返回JSON数据


