# UESTCers Android

<p align="center">
  <img src="app-icon.png" alt="UESTCers App 图标" width="180">
</p>

<p align="center">
  成电人的独立、非官方社区 Android 客户端
</p>

<p align="center">
  <a href="https://uestcers.com">访问网站</a> ·
  <a href="https://uestcers.com/70">70 周年专题</a> ·
  <a href="https://github.com/lzlz1618/uestcers-app/releases/latest">下载最新版</a> ·
  <a href="INSTALL.md">安装说明</a> ·
  <a href="https://uestcers.com/privacy">隐私政策</a>
</p>

> UESTCers 由社区独立维护，不是电子科技大学官方网站，不代表或隶属于电子科技大学。社区审核不是学校官方身份认证。Android 客户端目前仅面向年满 18 周岁的用户。

## 下载

请从本仓库的 [GitHub Releases](https://github.com/lzlz1618/uestcers-app/releases/latest) 下载 `uestcers-1.2.1-4.apk`。

当前版本：`1.2.1 (4)`

SHA-256：

```text
1B9425EEEAE03F94BE4F14F4DE5592A27575F100878ADAF04A2C098B5F772C4D
```

只信任本仓库 Releases 中的安装包。来自网盘、群文件或第三方站点的 APK 可能被修改或重新打包。

## 这个 App 可以做什么

- 申请一个 2–32 位 UESTCers 用户名；
- 浏览使用五张成都、上海实景照片制作的高清七秩成电离线相册；
- 浏览审核通过的成员、公开主页和社区内容；
- 发布、点赞、评论、回复和关注；
- 互相关注后使用私信；
- 举报、屏蔽和申请删除账号；
- 从系统浏览器进入独立的 Cloud Mail 邮箱系统。

网站与 App 使用同一套 UESTCers 服务端数据。社区账号和 Cloud Mail 邮箱账号相互独立，密码不要混用。审核通过也不会自动创建邮箱；邮箱需由管理员另行开通。

## 安装和开始使用

完整步骤见 [INSTALL.md](INSTALL.md)。简要流程：

1. 下载 Releases 中的 APK；
2. Android 提示时，仅为当前浏览器或文件管理器允许“安装未知应用”；
3. 安装完成后可重新关闭该权限；
4. 首次启动时阅读非官方声明并确认已年满 18 周岁；
5. 申请加入后保存私密申请进度链接，从该链接查看人工审核结果。

未安装 App 也可以直接使用 [uestcers.com](https://uestcers.com)。

## 网站新增入口（2026-10-02）

- **高清名片**：打开自己的公开主页，选择“保存名片”，可下载带主页二维码的 1600×2000 PNG，自行选择展示学院、年份、From 和已启用邮箱。
- **[申请与邮箱状态](https://uestcers.com/status)**：社区账号登录后查看进度与一次性密码交付；待审核用户仍使用保存的私密申请链接。
- **[成电记忆](https://uestcers.com/memories)**：登录后分享校园故事和可选高清照片，管理员审核后公开；可按年份、校区筛选，作者可撤回。

这三项目前通过网站浏览器使用，现有 Android `1.2.1 (4)` 安装包未重新编译。网站与 App 原有功能仍共用服务端数据，邮箱依旧在独立 Cloud Mail 中使用。

## 隐私、安全与反馈

- 隐私政策：[uestcers.com/privacy](https://uestcers.com/privacy)
- 举报入口：[uestcers.com/report](https://uestcers.com/report)
- 账号删除：[uestcers.com/delete-account](https://uestcers.com/delete-account)
- 安全报告：[SECURITY.md](SECURITY.md)
- 普通问题和建议：使用本仓库的 GitHub Issues

请勿在公开 Issue 中提交密码、私密申请链接、个人联系方式或其他用户数据。

## 为什么这里不公开完整源码

本仓库只负责官方入口、安装说明和 APK 发布。网站后端、管理脚本和基础设施配置保存在所有者的私有仓库中，以降低针对性攻击、误提交密钥和第三方冒用重新打包的风险。生产数据库、用户资料、服务密钥及 Android 签名密钥均不会上传到本公开仓库。

本仓库未授予第三方重新打包、冒用 UESTCers 名称或图案发布衍生 APK 的许可。

