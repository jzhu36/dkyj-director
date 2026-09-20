# 大开眼界导演台 · DKYJ Director

<img src="assets/logo.png" width="180" alt="大开眼界导演台 Logo">

**产品介绍、使用说明与 Mac / Windows 客户端下载。Lite 与 Pro 使用同一安装包。**

## 下载 0.8.0-preview.9

- [Mac 客户端](downloads/dkyj-client-0.8.0-preview.9-macos.zip)
- [Windows 客户端](downloads/dkyj-client-0.8.0-preview.9-windows.zip)
- [对应源码获取说明](SOURCE.md) · [版本发布页](https://github.com/wangjiake666/dkyj-director/releases/tag/v0.8.0-preview.9)

下载 ZIP 后解压，Mac 双击“打开大开眼界导演台.command”，Windows 双击对应 .cmd 启动器。首次启动按提示安装依赖。

## 能做什么

- 描述场景，由用户连接的 Agent 与 Blender MCP 搭建简化白模。
- 编辑人物走位与关键帧，安排镜头节奏。
- 使用手机双摇杆、体感或手柄操控摄影机；分别调节移动与转向速度。
- 导出镜头画面和俯视空间说明，两路各为 16:9，可独立或上下合并。
- 切换项目与场次，保留场景模型用于后续预演。

## Lite 与 Pro

| 功能 | Lite 免费版 | Pro |
| --- | --- | --- |
| 每项目保存场次 | 3 个，可删旧腾位 | 不限 |
| 手机／键盘录制 | 支持 | 支持 |
| 手柄预览 | 支持 | 支持 |
| 手柄录制与轨迹保存 | 官方场景试录 | 正式项目可用 |
| 视频导出 | 带预览水印 | 无水印 |

Pro v1 激活码无到期日期，授权覆盖当前商业大版本。[前往爱发电选择 Pro 商品](https://afdian.com/a/DKYJ666?tab=home)，获取激活码后在客户端授权面板离线激活。

## 使用环境

电脑需要 [Blender 5.2](https://www.blender.org/download/) 与 [Python 3.11–3.14](https://www.python.org/downloads/)。Mac 使用 Safari，Windows 使用 Edge；手机使用 iPhone Safari，同一 Wi-Fi 扫码连接。体感需要 HTTPS 与动作权限。

AI 场景制作需要用户自行连接 Agent、Blender MCP 与 DKYJ MCP；提交描述不会自动启动未连接的模型。Windows 显卡、iPhone 与 PS5 的完整设备验收范围请向作者咨询。

## 联系

抖音：王夹克 · 微信公众号：大开眼界AI · 合作邮箱：826701673@qq.com

## 历史分发说明

旧版客户端已统一由当前版本替代。升级前保存工程并退出 Blender，在新目录安装后迁移 projects/ 与 takes/，不要搬运旧 .venv/ 或 runtime/。之前分发版本附带的许可证与接收者已有权利不变，参见 [对应源码说明](SOURCE.md)。

[更新记录](CHANGELOG.md)
