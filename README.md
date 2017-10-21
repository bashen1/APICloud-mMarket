# APICloud-mMarket

<div class="outline">
    
[androidScore](#a0)

[iosShowStar](#a1)

[iosShowComment](#a2)

[iosShowDetail](#a3)

</div>

#**概述**

此模块可以跳转至应用商店具体应用详情，可以调用iOS打分，APP排名利器

<div id="a0"></div>

# **androidScore**

打开安卓市场应用页
androidScore({params})

## params

pkg:
-类型：字符串
-描述：应用的包名

## 示例代码

```js
var mMarket = api.require('mMarket');
var param = {
    pkg : 'com.tencent.mobileqq'   //应用的包名
};
mMarket.androidScore(param);
```

## 可用性

Android系统
可提供的1.0.0及更高版本

<div id="a1"></div>

# **iosShowStar**

打开当前应用的应用内评分
iosShowStar({params})

## params

appid:
-类型：字符串
-描述：应用id
-例子：https://itunes.apple.com/cn/app/id1044283059   1044283059就是应用ID


## 示例代码

```js
var mMarket = api.require('mMarket');
var param = {
    appid : '1044283059'
};
mMarket.iosShowStar(param);
```

## 可用性

iOS系统
可提供的1.0.0及更高版本

<div id="a2"></div>

# **iosShowComment**

打开App Store应用评分评论页
iosShowComment({params})

## params

appid:
-类型：字符串
-描述：应用id
-例子：https://itunes.apple.com/cn/app/id1044283059   1044283059就是应用ID


## 示例代码

```js
var mMarket = api.require('mMarket');
var param = {
    appid : '1044283059'
};
mMarket.iosShowComment(param);
```

## 可用性

iOS系统
可提供的1.0.0及更高版本


<div id="a3"></div>

# **iosShowDetail**

打开App Store应用详情
iosShowDetail({params})

## params

appid:
-类型：字符串
-描述：应用id
-例子：https://itunes.apple.com/cn/app/id1044283059   1044283059就是应用ID


## 示例代码

```js
var mMarket = api.require('mMarket');
var param = {
    appid : '1044283059'
};
mMarket.iosShowComment(param);
```

## 可用性

iOS系统
可提供的1.0.0及更高版本
