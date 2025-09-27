<div align="center">
<h1>OpenWrt — 云编译</h1>

## 特别提示

- **本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任！**

- **本固件禁止用于任何商业用途，请务必严格遵守国家互联网使用相关法律规定！**

## 项目说明
- 默认管理地址：**`192.168.2.1`** 默认用户：**`root`** 默认密码：**`none`**
- 源码来源：[LiBwrt](https://github.com/LiBwrt-op/openwrt-6.x) [VIKINGYFY](https://github.com/VIKINGYFY/immortalwrt)

## 仓库说明
- 本人 Fork 的仓库：[VIKINGYFY](https://github.com/VIKINGYFY/immortalwrt),[LibWrt](https://github.com/LiBwrt/openwrt-6.x)，内容大体一致。
- `ImmortalWrt` 和 `LibWrt` 相互印证。
- `LibWrt` 因为 DTS 更为丰富，所以支持更多的机型。

## 定制固件
- 首先要登录 Github 账号，然后 Fork 此项目到你自己的 Github 仓库。
- 修改 `configs` 目录对应的文件添加或删除插件，或者上传自己的 `xx.config` 配置文件。
- 不需要的软件包请把 `y` 改成 `n` ，仅在前面添加 `#` 是无效的。
- 插件对应名称及功能请参考恩山网友帖子：[OpenWrt软件包全量解释](https://www.right.com.cn/FORUM/forum.php?mod=viewthread&tid=8384897)。
- 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `ImmortalWrt-IPQ60XX.yml/LiBwrt-IPQ60XX.yml` 文件内的"#编译配置"选项处修改。
- 添加或修改 `xx.yml` 文件，最后点击 `操作` 运行要编译的 `workflow` 即可开始编译。
- 编译大概需要 1-2 小时，编译完成后在仓库主页 [Releases](https://github.com/krisxu23/openwrt-ci-VIKINGYFY/releases) 对应 Tag 标签内下载固件。
