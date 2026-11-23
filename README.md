# 红果净化

适用于红果短剧与红果漫剧，支持液态玻璃底栏、界面净化、广告控制、播放增强与视频保存。

[官网](https://hongguo.goforit.si) · [下载最新版本](https://github.com/5hux1n/hongguofn/releases/latest) · [插件源](https://apt.mjh.im) · [问题反馈](https://pingme.pm/hongguo)

本仓库用于发布插件安装包与使用说明。

## 安装

适用于 **iOS 15 及以上**，支持红果短剧与红果漫剧，提供越狱、巨魔与证书签名安装方式。

在 Sileo 或 Irisin 添加 `https://apt.mjh.im/`，搜索“红果净化”，选择对应越狱方案安装。也可以从 [Releases](https://github.com/5hux1n/hongguofn/releases) 下载 DEB。

| 安装方式 | 下载 |
| --- | --- |
| Rootless | [arm64 DEB](https://github.com/5hux1n/hongguofn/releases/download/v2.2.7/hongguofn_2.2.7_arm64.deb) |
| RootHide | [arm64e DEB](https://github.com/5hux1n/hongguofn/releases/download/v2.2.7/hongguofn_2.2.7_arm64e.deb) |

巨魔或证书签名安装：下载 [插件注入文件](https://github.com/5hux1n/hongguofn/releases/download/v2.2.7/hongguofn_2.2.7.dylib)，将其注入目标 App 后，再通过巨魔或证书签名安装。

插件入口在「我的 → 设置 → 红果净化」。双指长按底部导航栏 1 秒也可以打开净化设置。

## 功能

- 液态玻璃：iOS 26 及以上使用原生玻璃效果，较低系统提供仿液态玻璃；支持参数调节与实时预览，适配 iPhone 和 iPad。
- 界面净化：按需隐藏挂件、推广入口、剧标签和播放页互动按钮。
- 导航设置：隐藏顶部频道、底部导航，自选默认启动页与首页频道。
- 播放增强：广告控制、时长与播放量显示、左右侧长按倍速、默认倍速和清晰度锁定。
- 清屏观看：自动清屏、超级清屏、隐藏状态栏及双指手势切换。
- 视频保存：App 内本地下载、保存到相册、进度提示及下载后自动保存。
- 更多功能：个人中心与侧边栏净化、红点隐藏、小说自动阅读和自动福利任务。

## 使用说明

在插件设置中选择需要的功能。自动福利需开启对应任务开关；保存到相册需允许照片权限。原生本地下载保存在 App 内，保存到相册后可在系统“照片”中查看。

## 2.2.7 更新

- 新增「显示听视频入口」和「听视频画面铺满」开关
- 新增禁用短剧灵动岛和活跃卡片
- 新增显示真实分享数量
- 新增首页和播放页组件大小、透明度调节，支持批量设置
- 新增首页横幅高度、图文尺寸和透明度调节
- 新增评论面板毛玻璃和文字颜色调节
- 新增「评论区保持视频尺寸」开关
- 修复评论动图保存后变成静态图的问题
- 优化液态玻璃参数页的分组和布局
- 优化推荐流整页问卷拦截
- 优化信息流小游戏推广拦截
- 优化 App Store 评分弹窗和好评引导拦截
- 移除强制显示 iPad 全屏播放按钮

完整版本历史见 [Releases](https://github.com/5hux1n/hongguofn/releases)。

维护者：[Junhong](https://mjh.im/)
