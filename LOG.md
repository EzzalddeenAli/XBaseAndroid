### 20171130（版本1.0.2）【已发布】
+ 解决了EventBus自动注册问题，取消自动注册。
+ 解决了LoadingDialogBUG，已经修复。
+ 解决了判断内存卡是否存在的BUG。


### 20171215（版本1.0.3）【已发布】
+ 优化Activity启动，改为从ActivityUtils启动。
+ 新增复制黏贴工具类ClipboardUtils。
+ 规范名称将Xbase改为XBase。
+ 将倒计时控件 改为单列模式，规范使用模式。
+ 整改校验框架，实现更全面的校验文本。

### 20171218（版本1.0.4）【已发布】
+ ActivityUtils.kill()会销毁全部Activity并杀死进程。不用再调用ActivityStack.getInstance().clearAllActivity();方法；
+ ActivityUtils新增Flag,Action参数
+ 移除蓝牙模块、移除校验模块，如需使用请单独引用。
+ 引入耗时操作线程池
+ 优化网页浏览器

### 20180108（版本1.0.5Final）【已发布】
+ 引入万能下拉刷新上拉加载更多
+ 优化框架，将kill函数移植到CommonUtils下，添加Service管理。

### 20180220（版本1.0.6.2）【已发布】
+ 规范包名，优化组件

### 20180301（版本1.0.6.3）【已发布】
+ 实现热应用更新
+ 优化应用

### 20180305（版本1.0.6.4）
+ 实现文件下载器
+ 优化webview
+ 优化广播通知

### 20180314（版本1.0.6.5）
+ 优化内部浏览器

### 20180403（版本1.0.7.0）
+ 修改ViewHolder方法为onBindView
+ 优化标题栏。EaseTitleBar修改为XBaseTitleBar
+ 优化Activity工具类。

### 20180704（版本1.0.8.1）
+ 新增XBasePermissionActivity权限申请更方便
+ GsonUtils新增toString方法。

### 20180725（版本1.0.9.3）
+ 移除XBasePermissionActivity  将功能移植到XBaseActivity  需要回调直接重写onPermissionSuccess，onPermissionError
+ 移除腾讯浏览器引擎。

### 20180810（版本1.0.9.4）
+ 增强XBaseBrowserActivity JS安卓交互功能。详情请看https://www.jianshu.com/p/de02e5629d3c

### 20181016（版本1.2.0）
+ 修复权限申请回调问题
+ 新增内置HTTP请求组件。
+ 移除Andfix热更新框架。无法解决6.0以上问题。
+ 优化浏览器引擎。加入cookie支持，文件选择支持，退出提示。

### 20181119（版本1.3.0）
+ 优化内置浏览器上传图片的问题。
+ 优化加密相关代码

### 20191102（版本1.3.1）
+ 升级第三方包
+ 优化webview相关功能

### 2019112（版本1.3.2）
+ 升级到androidx


### 20191224（版本1.3.3）
+ 优化XBaseFragment
+ 重命名ConfigUtils 为 SpUtils,ProjectUtils 为 WorkGroupUtils，AppConfig为PropertiesHelper
+ 将GSON 换为 FastJSON ，升级glide版本为1.10.0
+ 解决Webview出现的崩溃问题

### 20191226（版本1.3.4）
+ 新增recyclerview，listview万能适配器（代码源自https://github.com/hongyangAndroid）
+ 增强DatabaseHelper工具