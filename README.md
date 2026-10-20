# colmo-hatoggle（HaToggle）

给 COLMO / 美的智慧屏用的小工具：在屏幕底部上滑，就能在 **系统桌面** 和 **Home Assistant**（或任意 App）之间秒切。

## 功能
- **快速上滑**：桌面 ⇄ 上次选的 App（默认 Home Assistant）
- **上滑并按住约 0.45 秒**：弹出 App 菜单，手指滑到目标松手即打开，它也会成为之后快速上滑的目标
- 设置页可勾选菜单里放哪些 App（默认：桌面、Home Assistant、Chromium）
- HA 在前台时自动屏蔽左右侧滑“返回”，防误退出
- 首次打开自动授权（利用屏自带 root），开机自启、后台保活

## 下载
点上面文件列表里的 **HaToggle-2.0.apk** → 右上角下载按钮（Download raw file）。公开仓库，无需登录。

国内访问 GitHub 慢的话，也可以在 Gitee 搜 **colmo-hatoggle**，内容相同。

## 安装（屏上全程完成，不用电脑）
1. COLMO 设置 → 关于本机 → 设备信息，连点「序列号」进入安卓设置
2. 安卓设置里搜索 **chromium** → 应用信息 →「打开」
3. 打开本仓库（或 Gitee 搜 colmo-hatoggle），点 HaToggle-2.0.apk 下载（提示“文件可能有害”点「仍然下载」）
4. 下载完点「打开」即自动安装；没看到提示就 菜单 → 下载内容 → 点 APK
5. 打开 HaToggle，自动授权完成即可使用

> 已在 Android 14、1920×720 的 COLMO 智慧屏实测。仅供个人学习交流，刷机/改动系统有风险，后果自负。
