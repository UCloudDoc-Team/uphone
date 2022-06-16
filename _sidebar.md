* [概览](/uphone/README.md)
* 产品介绍   <!-- 以下是参考的目录模版，旨在建议产品文档应该包含的内容模块。实际章节划分可根据实际内容进行调整 -->
   * [什么是云手机](/uphone/_whatUphone.md)
   * [功能与优势](/uphone/_function.md)
   * [应用场景](/uphone/_application.md)

* UPhone产品
    * [注册账号](/uphone/guide.md#注册账号)
    * [创建云手机](/uphone/guide.md#创建云手机)
    * [独立IP与共享带宽](/uphone/guide.md#独立公网IP)
    * [群控管理](/uphone/guide.md#群控管理)
    * [文件上传](/uphone/guide.md#文件上传)
    * [一键新机](/uphone/guide.md#一键新机)
    * [开关ROOT](/uphone/guide.md#开关ROOT)
    * [设置GPS](/uphone/guide.md#设置GPS)
    * [产品计费](/uphone/price-uphone.md#产品计费)
    
* UPhoneServer产品 
    * [服务器配置](/uphone/price.md#云手机服务器)
    * [创建云手机服务器](/uphone/guide.md#创建云手机服务器)
    * [自制手机镜像](/uphone/guide.md#自制镜像)
    * [使用ADB](/uphone/guide.md#使用ADB)
    * [产品计费](/uphone/price.md#产品计费)
      
* 常见问题
  * [功能相关](/uphone/FAQ.md#功能相关)
  * [体验相关](/uphone/FAQ.md#体验相关)
  * [二次开发](/uphone/FAQ.md#二次开发)

* 管理API
  * [API 文档](https://cms-docs.ucloudadmin.com/api/uphone-api/README)
  * [API SDK](https://cms-docs.ucloudadmin.com/tools)
  * [AOSP高阶功能](/uphone/_sysapplication.md)

* 客户端SDK

 * Android SDK
   * [SDK下载](/uphone/sdk.md#SDK下载)
   <details>
   * <summary> 工程配置 </summary>
      <p> [配置权限](/uphone/sdk.md#配置权限)</p>      
        <p> [导入SDK包](/uphone/sdk.md#导入SDK包)</p> 
        <p> [代码混淆](/uphone/sdk.md#代码混淆) </p>
        
  </details>
    * 快速入门
        * [注册云手机状态监听器](/uphone/sdk.md#注册云手机状态监听器)  	
        * [初始化云手机sdk](/uphone/sdk.md#初始化云手机sdk)   	 
        * [连接云手机](/uphone/sdk.md#连接UPhone)       
        * [断开云手机](/uphone/sdk.md#断开UPhone)  
    * 接口说明
        * [初始化sdk](/uphone/sdk.md#初始化sdk) 
        * [连接云手机](/uphone/sdk.md#连接云手机)  
        * [断开云手机](/uphone/sdk.md#断开云手机)      
        * [重新连接云手机](/uphone/sdk.md#重新连接云手机)      
        * [设置分辨率](/uphone/sdk.md#设置分辨率)         
        * [发送指定按键](/uphone/sdk.md#发送指定按键)       
        * [设置静音](/uphone/sdk.md#设置静音)     
        * [是否支持直播](/uphone/sdk.md#是否支持直播)    
        * [开启直播](/uphone/sdk.md#开启直播)    
        * [停止直播](/uphone/sdk.md#停止直播)    
        * [获取视频流基本参数](/uphone/sdk.md#获取视频流基本参数)    
        * [获得网络延时](/uphone/sdk.md#获得网络延时)  
        * [获得丢包率](/uphone/sdk.md#获得丢包率)     
        * [获取网络速度](/uphone/sdk.md#获取网络速度)    
        * [获取用户最后一次操作时间戳](/uphone/sdk.md#获取用户最后一次操作时间戳)     
        * [获得版本号](/uphone/sdk.md#获得版本号)
 * iOS SDK 
    * [SDK下载](/uphone/ios_sdk.md#SDK下载)  
    * [工程配置](/uphone/ios_sdk.md#工程配置)              
        * [导入SDK](/uphone/ios_sdk.md#导入SDK)     
        * [配置权限](/uphone/ios_sdk.md#配置权限) 
    * [接入步骤](/uphone/ios_sdk.md#接入步骤)  
        * [初始化SDK](/uphone/ios_sdk.md#初始化SDK)           
    * [接口说明](/uphone/ios_sdk.md#接口说明)
        * [连接云手机](/uphone/ios_sdk.md#连接云手机)  
        * [断开云手机](/uphone/ios_sdk.md#断开云手机)      
        * [重连云手机](/uphone/ios_sdk.md#重连云手机)      
        * [设置分辨率](/uphone/ios_sdk.md#设置分辨率)         
        * [获取网络延时](/uphone/ios_sdk.md#获取网络延时)       
        * [获取SDK版本号](/uphone/ios_sdk.md#获取SDK版本号)     
        * [云手机清理后台任务](/uphone/ios_sdk.md#云手机清理后台任务)    
        * [云手机返回到桌面](/uphone/ios_sdk.md#云手机返回到桌面)    
        * [云手机返回到上一级界面](/uphone/ios_sdk.md#云手机返回到上一级界面)    
        * [获取网络速度](/uphone/ios_sdk.md#获取网络速度)    
        * [开始直播](/uphone/ios_sdk.md#开始直播)  
        * [停止直播](/uphone/ios_sdk.md#停止直播)     
        * [获取当前播放器截屏](/uphone/ios_sdk.md#获取当前播放器截屏)    
        * [检测当前截屏是否黑屏](/uphone/ios_sdk.md#检测当前截屏是否黑屏)     
        * [获取丢包率](/uphone/ios_sdk.md#获取丢包率)
        * [获取视频流基本参数接口](/uphone/ios_sdk.md#获取视频流基本参数接口)
        * [获取用户最后一次操作时间戳](/uphone/ios_sdk.md#获取用户最后一次操作时间戳)
        * [是否支持直播](/uphone/ios_sdk.md#是否支持直播)
        * [静音开关功能](/uphone/ios_sdk.md#静音开关功能)
     * [注意事项](/uphone/ios_sdk.md#注意事项)
 * H5 SDK
     * [接入步骤](/uphone/h5-sdk.md#快速入门amp集成SDK)
     * [接口说明](/uphone/h5-sdk.md#API接口)

