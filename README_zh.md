[![点击这里下载](https://img.shields.io/badge/⬇_下载-点击这里-success?style=for-the-badge)](https://github.com/trgkyle/t-creator-user-guide/releases)

# 🎬 T Creator v1.0.0 - AI 图像与视频创作工具 [![English](https://img.shields.io/badge/English-blue)](README.md) [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md)

**T Creator** 是一款桌面应用，使用大型模型以极低成本创建 AI 图像和视频。使用 **Nano Banana** 生成图像，**Veo 3** 生成视频，更多模型（Grok、Sora、Seedance 2.0）即将推出。支持 **Windows** 和 **Mac**；网页版即将推出。

-----

## ✨ 主要功能

* **🖼️ AI 图像生成：** 文本转图像、组件转图像（多张参考图）。模型：**Nano Banana Pro**。
* **🎬 AI 视频生成：** 文本转视频、帧转视频（图像+运动）、组件转视频。模型：**Veo 3**（Fast / Quality）。
* **⚙️ 完整控制：** 选择模型、画质、宽高比；视频可选时长。批量 prompt（每行一个），支持 Start / Pause / Stop。
* **📊 实时进度：** 查看每个 prompt 的状态与进度；在应用内预览并打开结果。
* **📂 自动下载：** 将图像和视频保存到指定文件夹（可选）。
* **📜 历史记录：** 浏览和预览过往生成。
* **🌐 多语言：** English、Tiếng Việt、中文。

-----

## 📥 安装

1. 打开 [Releases](https://github.com/trgkyle/t-creator-user-guide/releases)。
2. 按系统下载安装包：
   - **Windows：** `.exe`（如 `T Creator Setup 1.0.0.exe`）。
   - **Mac：** `.dmg`（如 `T Creator-1.0.0-arm64.dmg`）。
3. 运行安装程序并打开 **T Creator**。

-----

## 📖 使用指南

### 入门

1. **注册 / 登录**  
   创建账号或登录。生成将消耗 Credits。

2. **打开 Scene Creator**  
   主界面为 **Scene Creator**：通过 prompt 创建图像或视频。

3. **选择标签页**  
   - **创建图像** — 文本转图像或组件转图像。  
   - **创建视频** — 文本转视频、帧转视频或组件转视频。

4. **设置选项**  
   - **模式：** 如 Text to Image、Components to Image、Text to Video、Frame to Video。  
   - **模型：** 如 Nano Banana Pro（图像）、Veo3 Fast / Veo3 Quality（视频）。  
   - **画质**、**宽高比**；视频另有 **时长**。

### 1. 图像：文本转图像

1. 选择 **创建图像** 标签，模式 **Text to Image**。
2. 输入一个或多个 prompt（每行一个；空行表示新 prompt）。
3. 点击 **Start** 运行。在右侧表格查看状态与预览。

### 2. 图像：组件转图像

1. 选择 **创建图像** 标签，模式 **Components to Image**。
2. 上传 1–5 张参考图（拖放或点击选择）。
3. 输入 prompt（每行一个）。每个 prompt 共用已上传的图片。
4. 点击 **Start**。

### 3. 视频：文本转视频

1. 选择 **创建视频** 标签，模式 **Text to Video**。
2. 输入 prompt（每行一个）。
3. 点击 **Start**。

### 4. 视频：帧转视频

1. 选择 **创建视频** 标签，模式 **Frame to Video**。
2. 上传 1–2 张源图像。
3. 输入 prompt（每行一个）。每个 prompt 应用于已上传图像。
4. 点击 **Start**。

### 5. 视频：组件转视频

1. 选择 **创建视频** 标签，模式 **Ingredients to Video**。
2. 上传最多 3 张参考图。
3. 输入 prompt 并点击 **Start**。

### 输出与下载

- **输出：** 每行显示 prompt、状态（pending / running / done / failed）和预览。点击预览可全屏查看。
- **自动下载：** 在底部开启 **Auto Download Image** 和/或 **Auto Download Video** 并选择文件夹。完成后将自动保存。

-----

## ⚙️ 设置与其他

- **Settings：** 语言（EN / VI / ZH）及其他应用偏好。
- **History：** 查看和预览以往的图像/视频任务。
- **Credits：** 使用量以 credits 计费；用尽时可充值。

-----

## 🤖 模型（当前与计划）

| 类型   | 模型             | 状态       |
|--------|------------------|------------|
| 图像   | Nano Banana Pro  | ✅ 可用    |
| 视频   | Veo 3 (Fast / Quality) | ✅ 可用    |
| 视频   | Grok             | 🔜 即将推出 |
| 视频   | Sora             | 🔜 即将推出 |
| 视频   | Seedance 2.0     | 🔜 即将推出 |

-----

## 💡 提示

1. **Prompt：** 尽量具体；描述越清晰效果通常越好。  
2. **批量：** 每行一个 prompt；空行分隔不同 prompt。  
3. **Pause / Stop：** Pause 暂停队列，Stop 取消剩余任务。  
4. **Credits：** 注意余额；不足时请充值。

-----

## 🔧 故障排除

| 问题 | 解决方法 |
| :--- | :--- |
| **登录失败** | 检查邮箱/密码；必要时使用忘记密码。 |
| **模型列表为空** | 确认有 credits 且能连上后端；稍后重试。 |
| **任务卡住/失败** | 检查网络；重试或使用更简单的 prompt。 |
| **自动下载未保存** | 确认文件夹有写入权限；必要时重新选择文件夹。 |

-----

## 📞 支持

- **Releases：** [github.com/trgkyle/t-creator-user-guide/releases](https://github.com/trgkyle/t-creator-user-guide/releases)
- **反馈：** 在项目仓库提交 issue。

-----

## 📦 版本

当前版本：**1.0.0**

-----

## 📜 版权声明

版权所有 © 2026 **Trường Nguyễn**。保留所有权利。

本软件为专有财产。未经授权，严禁复制或分发。

---

**由 Trường Nguyễn 用 ❤️ 制作**
