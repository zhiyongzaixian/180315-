## 小程序
### 什么是小程序？
  1. 无需下载，用完即走(体积太小，刚发布的压缩包体积最大不能超过1M， 2017年4月将1M提升2M)
### 小程序特点？
  1. 体积小
  2. 同app进行互补的，可以实现app基本的功能
  3. 微信扫一扫或者是搜索就可以去下载
  4. 开发周期短，成本较低
### 适配方案
  1. viewport适配 width = device-width
  2. 单位： rpx
  3. iphone6： 1rpx = 1物理像素 = 0.5px   dpr = 物理像素/设备独立像素 = 2
### 重要的文件
  1. wxml view结构 ---> html
  2. wxss view样式 ---> css
  3. js view行为 ---> js
  4. json文件： 数据 && 配置
### 注册小程序： App（）
### 注册页面 Page（）
### 数据绑定： 
  1. 在data中初始化页面需要的数据，在页面可以直接使用
### 事件(冒泡事件 || 非冒泡事件)
  1. 冒泡事件： bind + 事件名
  2. 非冒泡事件： catch + 事件名
  
