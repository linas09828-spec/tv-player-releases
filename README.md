# 在线影视 · 安装包发布

本仓库只放编译好的安装包，不含源码。

## 下载

在 [Releases](https://pub-ef748f44e98d4dc7a41a4af646dfac0f.r2.dev/zaixian-yingshi.ipa) 里下载最新版
`zaixian-yingshi.ipa`（滚动更新，链接固定），用 TrollStore 或 Sideloadly
等方式自签安装。

## 安卓版

[下载安卓版安装包（APK）](https://pub-ef748f44e98d4dc7a41a4af646dfac0f.r2.dev/ZaixianYingshi-android.apk)

手机、电视或模拟器上安装：`adb install ZaixianYingshi-android.apk`，
或直接把 APK 传到设备上点开装。现在是正式签名版，正式版之间可直接
覆盖安装、源都在。音乐、云盘、KTV 都已接上。

## Windows 版

[下载 Windows 版安装包（zip）](https://pub-ef748f44e98d4dc7a41a4af646dfac0f.r2.dev/ZaixianYingshi-win-x64.zip)

解压后双击 ZaixianYingshi.exe。第一次用要先装 .NET 8 桌面运行时（免费，微软官网下载）。

## macOS 版

[下载 macOS 版安装包（zip）](https://pub-ef748f44e98d4dc7a41a4af646dfac0f.r2.dev/ZaixianYingshi-mac.zip)

解压后把“在线影视.app”拖进应用程序文件夹，第一次打开右键点它选“打开”。支持 2014 年款 Intel Mac（macOS 12 及以上）。

## 这是什么

纯播放器外壳，不带源、不登录、不用后端：点播源、直播订阅、音乐台、电台
都由使用者自己在 App 里添加，只存在本机。覆盖安装保留数据，删 App 重装
后要重新添加。

- **影视**：影视区右上角 + 加源；含 `api.php` 的是接口源，其余是网站源（globe 图标，点开即网站）。
- **直播**：直播页右上角 + 菜单里加台 / 加订阅链接；订阅 m3u/txt 链接整批导入；分组点标题折叠/展开；订阅左滑有更新、复制、删除。
- **音乐**：音乐区右上角 + 加音乐台；填了账号密码的是 Subsonic 音乐台，都空着的是网站。
- **全球广播**：广播区右上角 + 加电台；流地址点台就播，网站链接点台就打开网站。
- **云盘**：WebDAV、Emby、Jellyfin、Plex、SMB、FTP、123云盘。
- **抓视频**：粘贴视频页面地址，抓真实 m3u8/mp4 地址直接播或保存；「我的链接」里存常用链接。
- **开发工具**：JSON 美化/压缩/校验、Base64、URL 编解码、直播源测速导出 live.txt、点播接口生成 TVBox 配置。

设置里只剩外观、墙纸、关于。

## 免责声明

本 App 仅为播放器外壳，不提供任何内容或源；源和订阅均由使用者自行添加，
仅存于本机；内容版权归源提供方所有，请合法使用。
