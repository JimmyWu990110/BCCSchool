# NO.6 Home Page

> Author:：徐肯
>
> Sid：17343130 



## 完成时间

2020.7.25



## 功能描述

网页首页，提供到其他各个页面的导航



## 注意事项





## 测试流程
#### 静态代码分析

+ VSCode自检测，消除所有warning和error



#### 单元测试

+ 导航栏是否能够正确选择当前页面对应的菜单项
+ 页面向下滚动时功能介绍部分能否正确显示

+ 各个链接是否能够正确跳转



## 技术笔记

纯静态页面，通过 HTML + CSS + JavaScript 实现

#### 第三方库

+ Bootstrap
+ JQuery
+ Animate.css



#### 主页导航栏

主体基于Bootstrap的导航栏、下拉菜单等组件，并进行内容以及样式的修改



#### 页面滚动相关动画实现

基于Animate.css实现，通过监听页面滚动事件并动态添加对应动画类名实现