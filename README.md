# 弹弹play

####  :tw-25b6: 介绍
弹弹play播放器：全功能本地视频+弹幕播放器

####  :tw-1f310: 下载

1. Windows版： [联想应用商店](https://lestore.lenovo.com/detail/10343)
2. 安卓版： [安卓概念版](https://gitee.com/xyoye/DanDanPlayForAndroid/releases)
3. iOS版（需要 TestFlight）： [AniXPlayer](https://testflight.apple.com/join/R6JotnNG)
4. UWP版： [微软商店](https://www.microsoft.com/store/productId/9nwpvd7t1hpw)
5. macOS版： [AniXPlayer for macOS](https://gitee.com/sun_sx/dandanplay_mac_update/releases)
6. Windows版网盘分流 [网盘1](https://www.123pan.com/s/KFBlVv-E4SA3.html) [网盘2](https://pan.baidu.com/s/13ACWJauADxbracesBCpcEg?pwd=rrv7)

####  :tw-1f4cb: 近期更新

[查看完整更新历史](https://www.dandanplay.com/blog.html)

**[Windows版][UWP版] v15.2.0**
- 媒体库番剧列表新增“左右分栏”排版
- 媒体库番剧弹窗中新增“其他文件”列表（将展示同文件夹下未匹配或可能被匹配错误的文件）
- 自动下载页面新增搜索框
- 新增部分后台运行与交互参数
- 媒体库启用新的底层存储机制：
  - 更新后首次启动时将自动迁移旧数据
  - 减少数据库文件损坏的概率
  - 扫描与文件信息更新过程中，新数据实时保存
  - 存储性能提升
- 媒体库文件列表新增“详细信息（紧凑）”排版方式
- 媒体库新增“磁盘未就绪状态检测”机制：当磁盘为未就绪状态时（如smb连接断开、U盘、移动硬盘拔出等），暂时不移除其中的文件记录。
- 媒体库番剧列表中，改善日语假名标题的分组
- 界面中增加部分文档链接
- FFmpeg内核支持快捷键开关字幕（Ctrl+L、H）
- 动画疯插件支持显示顶部/底部弹幕
- 修复AI语音识别功能中识别ffmpeg文件夹错误的问题
- 修复媒体库文件浏览器浏览位于根目录的文件时，文件显示错误的问题
- 修复“添加更多弹幕”窗口不能添加特定格式网址的问题

**[Windows版][UWP版] v15.1.0**
- 新增 FFmpeg 播放器内核
- 媒体库：番剧列表新增大图、中图、小图、列表、纯文字模式切换
- 媒体库：文件列表新增详细信息、平铺模式切换
- 媒体库：番剧弹窗增加上一个和下一个按钮，支持按ESC关闭弹窗；文件列表右键菜单可以打开文件所在位置。
- 新增“网络串流内核”设置，可以选择在串流网络视频时使用的播放器内核，也可以通过“弹幕外挂”拉起pot/mpv/mpc。
- 设置-在线服务页新增“弹幕功能”总开关。关闭后，加载视频时将不再读取弹幕，但仍可以手动加载在线或本地弹幕。
- 支持安卓概念版新版投屏协议
- 向安卓版投屏时，支持按照PC版进度续播，投屏退出后支持记录当前视频的播放进度
- “选择弹幕库”窗口中支持搜索剧集列表
- 修复媒体库添加文件夹时路径检查的问题
- 修复调整限速导致崩溃的问题
- 更新软件内帮助链接

**[Windows版][UWP版] v15.0.0**
- 启用全新媒体库界面：整合本地数据和关注列表，支持更多维度展示和筛选
- 修复部分情况下播放器可能无法启动的问题
- 修复吐槽插件解析问题
- 修复按 Ctrl+Enter 后弹幕发送框未自动获得焦点的问题
- 修复在使用 Windows 10 新版输入法时无法响应快捷键的问题
- 修复输入法候选框出现时弹幕发送框被隐藏的问题


####  :tw-1f4ac: 用户反馈

1. [官方反馈社区](https://support.qq.com/products/104929)
2. 本项目Issue区
