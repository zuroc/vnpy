# vn.py 
基于python的开源交易平台开发框架

## 2015/3/26项目状态##
因为有不少人问CTP的接口，正好我最近的项目也要用到，就把开发CTP封装的工作提前了。

CTP的python封装发布在vn.ctp文件夹下： 
 
1. 封装使用的API是最新支持期货交易所期权的6.3.0版本  
2. md部分已经完全经过了测试  
3. td部分只进行了少量测试，接下来几天会继续，测试仅会覆盖和交易相关的函数（银期转账等等测试大家有需要自己做吧）

## 2015/3/3项目状态 ##
目前完成：  

1. 华宝证券的LTS API的python封装，发布在vn.lts文件夹下  
2. 事件驱动引擎，发布在vn.event文件夹下  

### vn.lts   ###
ltsapi：华宝证券官方的LTS C++ API  
pyscript：用于自动生成重复度较高的封装代码的python脚本  
vnltsmd：行情API的封装源代码和测试脚本  
vnltstd：交易API的封装源代码和测试脚本  

### vn.event ###
eventType：定义事件类型常量  
eventEngine：包含事件驱动引擎实现  

## 下一步计划 ##
1. API封装、编译、使用方面的教程
2. 事件驱动引擎原理、使用方面的教程
3. 基于API和引擎开发的LTS交易客户平台（因为华宝没有提供官方的LTS交易软件，目前的两个实现分别是基于C++的尔易终端和基于.COM封装的盈佳终端）
4. 策略引擎接口

## 联系作者 ##
作者知乎名：用python的trader，想要联系作者可以通过知乎私信。

## License ##
MIT

