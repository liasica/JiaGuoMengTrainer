# 家国梦自动化
> 自v0.10起，不再提供`.txt`的源码，需要改源码的下载`.mdq`导入按键精灵后修改

**善用搜索引擎, 请勿做伸手党, PS: 人人都讨厌伸手党 [提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)**  
**注意**  
~~断网模式会有几率触发按键精灵崩溃/假死~~(据反馈，我本人没有碰到过), 请慎用, 最好`等待`或`重启`  
[演示](https://www.bilibili.com/video/av69603157)

## 当前版本
> 最近忙于使用`Go + OpenCV + TensorFlow`实现全自动化辅助功能, 以便丢掉按键精灵~全分辨率兼容且可以实现远程管理 / 网页管理 / 手机管理 还有其他各种任何想要的功能, 可以真正做到远程挂机远程管理, 自动管理, 同时会提供开放api给各位大佬(nga论坛上的一堆大佬) 方便让各位大佬做的自动升级策略以api的形式提供给我的辅助, 这样的话真正做到了无人值守自动升级(还要人干啥?)

- [v1.05](https://github.com/liasica/JiaGuoMengTrainer/releases/tag/1.05-fix)
- [社区版 -by @hentaiFly](https://github.com/liasica/JiaGuoMengTrainer/issues/31)

## 版本规划
- v1.1 更新OCR识别, 准确度更高
- v1.2 策略政策升级
- v2.0 使用golang重构, 实现网页 / 远程管理

## 需求
- windows
- 安卓模拟器
- [按键精灵手机助手(3.3.5)](http://www.mobileanjian.com/) / [按键精灵3.3.5](http://www.mobileanjian.com/)
- 正式版为: 1920 × 1080 480DPI (从v1.0开始, tip: 设为指定分辨率后手动拖放模拟器窗口不影响)
- v1.0以下版本分辨率 540 × 960 240DPI

## 如何提交反馈
[创建issue](https://github.com/liasica/JiaGuoMengTrainer/issues/new)，注：其他渠道的反馈不一定看得到

## 一些问题
- [如果启用按键精灵没反应，可以尝试使用更低版本的按键精灵 - @Srainsama](https://github.com/liasica/JiaGuoMengTrainer/issues/10)

### 自适应分辨率已知问题
> 我自己测试出的

- 无法防卡住
- 货物无法识别数量, 解决办法是每次强制拖动三次

## 使用教程
[使用说明](https://github.com/liasica/JiaGuoMengTrainer/wiki)  
只运行一次解决办法: [重复运行](https://github.com/liasica/JiaGuoMengTrainer/wiki/4.%E8%87%AA%E5%8A%A8%E5%8C%96%E8%AE%BE%E5%AE%9A#%E9%87%8D%E5%A4%8D%E8%BF%90%E8%A1%8C)

## 视频教程
https://www.bilibili.com/video/av69813206/

## 已有BUG
- ~~选择多个自动升级建筑会错乱 请暂时只选择一个自动升级建筑~~ 已修复

## 演示
> 个人比较懒, 谁能提供个手把手的教学视频或者图文教程欢迎提交PR  

https://www.bilibili.com/video/av69603157/

## 兼容
> 理论上移动设备只要按键精灵支持, 本脚本就支持, 但是会有分辨率的问题, 所以大家最好还是用模拟器挂机吧

- 模拟器 `兼容`
- Android手机 `未测试`
- iPhone `未测试`

## 格子

> 九宫格, 从左到右从上到下 1-9

| 7 | 8 | 9 |  
| 4 | 5 | 6 |  
| 1 | 2 | 3 |  

## 已实现功能
- [x] 自动收集金币
- [x] 自动按需升级建筑
- [x] 自动按需收集货物
- [x] 收集货物跳过时加速火车运行速度（重启游戏赶走火车，暂时不可配置，不喜欢重启就不要跳过）
- [x] UI界面配置
- [x] 可选择关闭重启游戏加速收货功能
- [x] 自动点击可能会对游戏持续性造成影响的按钮
- [x] 自动开启游戏
- [x] 跳过收货后断网加速火车(断网模式会有几率触发按键精灵崩溃/假死, 请慎用, 最好`等待`或`重启`)
- [x] 用户选择是否自动收金币
- [x] 卡死检测

## 待完善功能
- [ ] 按自定义策略自动升级政策

## 待做功能
- [ ] 使用其他语言做成APP且可配置
- [ ] 远程网页管理(管理设定 / 策略 / 查看当前截图)
- [ ] 三段式存钱
- [ ] 相册/红包多于指定数量自动开相册/红包
- [ ] 定时自动更换收货建筑, 收货完成后自动更换原来的建筑收割金币
- [ ] 自动升级终止等级
- [ ] 定时重启游戏

## 关于误差
自动收集货物有一定误差率, 简单测试准确度大概在~~`90%`又挂了好久统计了下最新数据是: ~~`78%`，够用了，目前没有发现特别严重的事故

### 编辑和使用
- 打开按键精灵手机助手
- 连接手机模拟器
- 导入脚本, 查看最新版本: https://github.com/liasica/JiaGuoMengTrainer/releases
