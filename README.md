<div align="center">

# 观语 · Guanyu

**以输出倒逼输入的 AI 语言学习助手**

精读 · 跟读 · AI 口语陪练 —— 不只英语，观照语言

</div>

---

观语是一款 **Android 语言学习 App**，核心理念是「**以输出倒逼输入**」：不是先背熟再用，而是在精读、跟读和真实对话中直接用起来。方法受经典英语学习路线启发，但产品不止步于英语——观照每一种语言，以用为本。

纯本地 App：**没有账号、没有服务器、学习数据全部存在你自己的手机里**。

## 功能

| 模块 | 你能做什么 |
|---|---|
| 📅 **今日** | 每日学习计划、打卡日历、学习统计，把坚持变成习惯 |
| 📖 **精读** | 英文素材阅读：点词即译、句子朗读、AI 逐句讲解 |
| 🎙 **口语** | AI 口语陪练：录音 → 语音识别 → 对话与纠错反馈 |
| ⚙️ **我的** | 学习档案、深色模式、学习提醒、TTS 音色与语速设置 |

## 下载

Android 安装包（APK），按 CPU 架构选择即可：

- [**GitHub Releases**](https://github.com/mumuopen/guanyu-app/releases/latest)
- [**Gitee Releases**](https://gitee.com/mumu-liquid/guanyu-app/releases/latest)

> 绝大多数现代手机用 **arm64-v8a** 包；老设备可尝试 **armeabi-v7a**。安装后 App 启动会自动检查更新，有新版会在应用内提示。

## 隐私

- 🔒 数据仅存本地（`SharedPreferences` / 本地文件），卸载即清空
- 🤖 AI 对话默认接 DeepSeek 等 OpenAI 兼容接口，**API Key 由你自己填写**，不上传任何学习记录
- 🔊 语音朗读支持内置离线引擎（sherpa-onnx），断网也能听

## 版本记录

| 版本 | 内容 |
|---|---|
| v0.10.0 | 更名「观语」· 全新图标 · GitHub / Gitee 双平台发布 |
| v0.8.0 | 应用内版本更新检查 · 深色主题 · 文件导入素材 |
| v0.7.0 | 学习提醒推送 · 发音评测升级 |
| v0.6.0 | 用户档案卡 · AI 学习方案 |
| v0.1.0–v0.5.0 | 精读 + 口语陪练上线 · 打卡日历 · 生词本 · 黑体显示 · TTS 升级 |

## 技术

Flutter · sherpa-onnx 离线 TTS · OpenAI 兼容 AI 接口

---

> 反馈与建议欢迎提交 [Issue](https://github.com/mumuopen/guanyu-app/issues)。
