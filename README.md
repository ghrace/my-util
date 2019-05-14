# my utils 

## usage
```
npm i ghr-util

import {randomStr} from 'ghr-util'

```
- timeout(ms)    等待毫秒
  
- randomStr    13位随机字符串 
  
- cutString   截取指定字节的字符串 
```js
/*
@param str 要截取的字符穿
@param len 要截取的长度，根据字节计算
@param suffix 截取前len个后，其余的字符的替换字符，一般用“…”
*/
 ``` 
- numberWithCommas   千分位

- isWeiXin   返回bool

- time  格式时间 
```js
// param 时间戳
//time 对象里方法
getTimeFormat m-d h:m
getTimeFormatYMD y-m-d
getTimeFormatAll y-m-d h:m:s
```
- checkLength   返回字节长度

- cloneObj,clone 

- checkCardNo   验证身份证号

- isURL,isValidUrl   url验证

- jsonp 
```js
options={
    url:'',
    callback:()=>{
    },
    data:{
    },
    success:(json)=>{},
    fail:()=>{},
    time:1//超时时间
}
jsonp(options)
```
- formatParams   data转 URL search 字符串

- cookie
```js
//{}方法
setCookie (name,value,time)
getCookie(name)
delCookie(name)
```
- randomString(len)   随机字符串

- parseUA    userAgent

- rem  rem配置

- GetRequest   获取url ?参数

- loadScript(url,cb)   加载js

- getRandomColor   随机颜色

- isUndefined undefined   判断

- debounce(fn,delay)

- throttle(fn,delay)