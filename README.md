# 弹弹play

#### ▶️ 介绍
弹弹play播放器：全功能本地视频+弹幕播放器

#### 🌐 下载

[从网盘下载（推荐）](https://kaedei.lanzouo.com/s/dandanplay)

1. Windows版： [联想应用商店](https://lestore.lenovo.com/detail/10343) | [GitHub发布页](https://github.com/kaedei/dandanplay/releases)
2. 安卓版： [安卓概念版Gitee](https://gitee.com/xyoye/DanDanPlayForAndroid/releases) | [安卓概念版GitHub](https://github.com/xyoye/DanDanPlayForAndroid/releases)
3. iOS版（需要 TestFlight）： [AniXPlayer](https://testflight.apple.com/join/R6JotnNG)
4. UWP版： [微软商店](https://www.microsoft.com/store/productId/9nwpvd7t1hpw)
5. macOS版： [AniXPlayer](https://github.com/sunsx9316/DanDanPlay_Experience/releases) | [NipaPlay-Reload](https://github.com/MCDFsteve/NipaPlay-Reload/releases)
6. Linux版： [NipaPlay-Reload](https://github.com/MCDFsteve/NipaPlay-Reload/releases)

#### 📜 近期更新

[查看完整更新历史](https://www.dandanplay.com/blog.html)

**[Windows版][UWP版] v16.0.0.0**
1. 番剧详情页中，支持选中一个或多个标签后搜索相关番剧
2. 【媒体库-远程连接】新增连接到 Plex 媒体服务器功能（会员功能）
3. 【设置-键盘】中新增自定义快捷键功能
4. 新增画面裁剪与缩放功能（“调整”边栏-宽高比、裁剪缩放）
5. 新增弹幕字体行高设置
6. EVR、VMR9、FFMpeg等内核支持实时调整画面宽高比
7. 新增弹幕保留区域设置，可以自定义顶部和底部的保留区域以避免遮挡视频内容
8. 高级番剧搜索结果中，新增显示制作团队信息（导演、系列构成、制作公司等）
9. 『弹幕外挂』控制台窗口支持调整并记忆窗口大小
10. 新增窗口吸附功能，允许拖拽窗口时自动吸附至屏幕边缘
11. 修复了播放列表页拖拽项目时可能报错的问题
12. 修复了输入弹幕内容时，鼠标指针被输入法窗口挡住导致输入框意外隐藏的问题
13. 优化媒体库中的番剧文件播放按钮

**[Windows版][UWP版] v15.14.0.0**
1. 新增芒果TV解析插件
2. 番剧详情页支持显示每一集关联的本地文件信息
3. 优化了登录失败、找回密码、找回用户名发生错误时的提示信息
4. 串流功能支持记录并选择之前的播放历史
5. 优化了部分页面的UI，优化了播放器首页的滚动性能
6. 修复了联网下载搜索字幕时网站错误的问题
7. 修复了优酷解析插件不支持新版网址的问题
8. 修复了关注部分番剧后，媒体库按名称浏览时无法显示界面的问题
9. 修复了从浏览器选择特定BiliBili分P视频时，丢失分P参数的问题
10. 修复了编辑媒体库Emby连接时无法填入过长的服务器地址的问题

**[Windows版][UWP版] v15.13.0**
1. 新增“修改播放器帧率上限”功能，可以配合其他软件对视频和弹幕补帧
2. 新增视频实时美颜功能
3. 画面优化界面中修改参数后会实时生效，不再需要点击“应用”按钮
4. 修复了弹幕来源页面加载时，弹幕偏移的分钟数显示错误的问题
5. 修复了部分情况下远程访问/安卓投屏播放视频时没有云同步观看历史的问题
6. 修复了多个 UI 细节问题

**[Windows版][UWP版] v15.12.0**
1. 适配弹弹play开放平台相关变更
2. 优化媒体库番剧信息刷新速度
3. SVP增加使用ffdshow（旧）的选项

**[Windows版][UWP版] v15.11.0**
1. 新增HDR手动开关
2. 新增视频色彩调整（动态范围修正、饱和度、对比度、亮度、伽马）
3. 支持在更多情况下（如串流）重新选择弹幕库并重新开始播放
4. 字幕翻译新增GPT-4o mini服务
5. 修复手动重新启动远程访问服务时报错的问题

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

#### 💬 用户反馈

[官方反馈社区](https://support.qq.com/products/104929)

[弹弹play文档站](https://doc.dandanplay.com/)
