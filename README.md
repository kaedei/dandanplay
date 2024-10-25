# 弹弹play

####  :tw-25b6: 介绍
弹弹play播放器：全功能本地视频+弹幕播放器

####  :tw-1f310: 下载

1. Windows版： [联想应用商店](https://lestore.lenovo.com/detail/10343)
2. 安卓版： [安卓概念版](https://gitee.com/xyoye/DanDanPlayForAndroid/releases)
3. iOS版（需要 TestFlight）： [AniXPlayer](https://testflight.apple.com/join/R6JotnNG)
4. UWP版： [微软商店](https://www.microsoft.com/store/productId/9nwpvd7t1hpw)
5. macOS版： [AniXPlayer](https://gitee.com/sun_sx/dandanplay_mac_update/releases) [NipaPlay](https://github.com/MCDFsteve/NipaPlay)
6. Windows版网盘分流 [网盘1](https://www.123pan.com/s/KFBlVv-E4SA3.html) [网盘2](https://pan.baidu.com/s/13ACWJauADxbracesBCpcEg?pwd=rrv7)

####  :tw-1f4cb: 近期更新

[查看完整更新历史](https://www.dandanplay.com/blog.html)

**[Windows版][UWP版] v15.10.0**
1. VLC内核支持HDMI/SPDIF音频直通功能
2. VLC内核支持新增强制开启杜比环绕（Dolby Surround）检测
3. EVR内核调用SVP补帧时将使用AviSynth处理
4. 番剧详情页增加显示动画的预告片、PV等视频链接
5. 播放列表页、播放列表边栏支持拖拽排序
6. 媒体库中右键菜单可以将本地文件/文件夹加入待扫描队列
7. 个人中心等界面的筛选、排序菜单将记住上次的选择
8. 媒体库远程连接增加右键菜单编辑功能
9. 媒体库远程连接登录状态过期时将显示提示
10. 优化远程访问Web页图片加载方式，将优先读取本机缓存
11. 优化磁力链解析种子文件时的缓存机制
12. 优化网络检测与修复工具的相关功能
13. 修复调用SVP补帧时，重复加载视频时无法继续启用的问题
14. 修复部分情况下系统托盘图标和右键菜单显示异常的问题
15. 修复远程访问启动时可能提示“重复添加”错误的问题
16. 修复远程访问Web页选择字幕可能出错的问题
17. 修复了通过网页播放时播放历史没有上传至服务器的问题

**[Windows版][UWP版] v15.9.2**
1. 下载器模块启动时将预热与DHT网络的连接（而不是等到启动首个任务才开始）
2. 新增通过DHT网络将磁力链解析为种子文件
3. “自动下载”页预览结果时会显示此资源是否已经在下载列表中
4. 修复了批量下载时速度可能降低至0的问题
5. 修复了串流播放时，可能会残留连接未断开的问题
6. 修复了串流播放时，长时间暂停后可能无法继续播放的问题

**[Windows版][UWP版] v15.9.0**
1. 媒体库远程连接（smb/webdav/onedrive）支持播放时加载远程磁盘上的同名弹幕文件
2. 加载包含分P投稿的弹幕时，支持自动检测分P并编辑时间，可以将多个分P拼接为一份弹幕
3. 媒体库网页版支持渲染ass格式的字幕
4. 自动下载规则兼容nyaa的RSS格式
5. 更新简繁转换词库，支持转换繁体中文相关俗语，修复部分转换错误
6. 串流播放时支持保存音轨、字幕轨、本地弹幕的选择偏好
7. 串流播放停止时，可以点击左下角播放按钮重新加载
8. 改善了串流播放和m3u8在线播放的成功率
9. 添加了嗅探功能对WebView2的版本号检查和提示
10. 更新下载器内核至v3.0.2
11. 修复了播放器长时间运行时，无法检测到DNS变化的问题
12. 修复连接部分WebDAV服务器时无法开始播放的问题
13. 修复了初始化WebView2时可能报错的问题
14. 修复搜索弹幕库出错时会意外报错的问题

**[Windows版][UWP版] v15.8.0**
- 更新下载内核至3.0.2
- 下载内核新增“自动封禁”功能，支持手动设定黑名单或自动封禁问题IP：
  - PeerID/客户端名称黑名单
  - IP地址黑名单（支持CIDR和IPv6）
  - 启发式进度检测功能，根据上传数据量、对方进度报告等条件自动封禁可能有问题的IP
  - 启发式检测支持自动封禁问题IP段
  - 自动加载网络上的共享IP封禁列表
  - 保存封禁历史，支持导出Excel格式的下载拦截和封禁历史的数据统计
- 媒体库新增连接 OneDrive 网盘功能，支持在线播放，支持浏览“与我分享”的文件/文件夹
- VLC内核新增设置：
  - 快速定位：提高跳转速度，但会降低精度
  - 渲染精度：将视频渲染为更高的分辨率，用于改善画质和字幕清晰度
- 新增记录播放历史&保存播放进度的阈值设定
- 下载任务信息窗口增加主动断开连接功能
- 文件识别/弹幕功能关闭时将显示提示
- 准备创建下载任务时，窗口将默认显示对应工具的默认下载位置
- 番剧详情-剧集列表右键菜单可以复制弹幕库ID
- 弹幕列表页会显示当前匹配的弹幕库名称
- 完善串流时断开重连功能的稳定性
- 修复了一个导致串流播放可能断开连接的问题
- 修复了无法串流部分大体积视频的问题
- 修复了在语音识别、字幕翻译窗口导出字幕可能出错的问题
- 修复了移除媒体库文件后导航栏选中项被切换的问题
- 修复了可能无法添加播放历史的问题


**[Windows版][UWP版] v15.7.0**
- VLC内核更新至官方v3.0.21
- 下载内核更新至3.0.0.0240
- 支持自定义使用的VLC内核版本（将文件放入指定位置后，重启播放器生效）
- 购买会员界面新增在线支付（微信支付、支付宝）
- 语音识别支持处理音频文件（如歌曲、有声小说等）
- 语音识别结果、翻译结果增加导出LRC歌词功能
- 媒体库、个人中心页面增加显示统计数字
- 部分窗口增加提示文字
- 优化部分界面报错提示
- 弹幕外挂弹幕层全局开关快捷键改为 Ctrl+Alt+CapsLock
- 修复异世界动漫解析问题
- 修复媒体库番剧详情中未显示部分关联视频文件的问题


**[Windows版][UWP版] v15.6.1**
- 媒体库新增连接到远程电脑上的弹弹play（PC版）功能，支持浏览文件、播放视频并自动匹配弹幕库、加载远程电脑上的外挂字幕文件
- 番剧详情页“元数据”区域改为表格形式展示
- 媒体库网页版优化：
  - 图片将按需加载（需要显示时才加载）
  - 优化番剧列表在手机上的展示样式
- 「弹幕外挂」支持CapsLock全局热键显示/关闭弹幕层
- 改进媒体库刷新文件的相关算法
- 优化了选择弹幕库窗口的手动搜索框，支持自动填入当前番剧名称
- 爱奇艺插件支持搜索
- 修复了爱奇艺插件无法解析的问题
- 修复了一个下载状态改变时可能会导致程序崩溃的问题
- 修复了媒体库初始化时有可能出错的问题
- 修复了下载器任务列表、媒体库文件列表中，多选状态错误的问题


####  :tw-1f4ac: 用户反馈

[官方反馈社区](https://support.qq.com/products/104929)
