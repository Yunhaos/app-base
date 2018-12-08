# app-base
用于原生App开发的基础工具包

# 使用
在项目的根目录的build.gradle中添加：<br/>
>allprojects {  
>>repositories {  
>>>google()  
>>>jcenter()  
>>>maven { url 'https://jitpack.io' }  
>>>maven { url "https://raw.githubusercontent.com/Yunhaos/app-base/master" }  

>>}  

>}  

在需要引用的模块中添加：<br/>
>`api 'com.yunhao.android.dev:app-base:0.0.1'`

# 最新版本号
>`v0.0.1`
