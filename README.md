# DmitriRender 简介与现况说明

📘 教学参考文章（Tutorial Article）：  
👉 [https://www.gdaily.org/22179/dmitrirender-60fps](https://www.gdaily.org/22179/dmitrirender-60fps)

🙏 如果你觉得这份整理有帮助，欢迎多多支持我们的网站！

---

## 中文说明

### 🔹 软件简介

**DmitriRender** 是一款基于 DirectShow 架构的实时视频插帧（frame interpolation）滤镜，由 Dmitri Zdorov 开发。它的主要功能是透过插入中间画面，将视频的帧率提升至 60fps 或更高，提供更流畅的播放效果。

该工具以简单易用、性能占用低为主要特点，可搭配 MPC-HC、PotPlayer 等播放器使用，是许多高帧率视频爱好者的选择之一。

---

### 🔹 开发状况

目前 **DmitriRender 已停止开发**，且 **官方网站已无法访问**。最终版本并未开源，也无社区接手持续维护。未来可能出现兼容性下降的情况，请用户注意风险。

---

### 🔹 附加文件与说明

- `dmitriRender_3.0.0.1.exe`：**3.0 稳定版安装文件**
- `dmitriRender_5.0.0.1_beta1.zip`：**5.0 测试版压缩安装文件**
- `Watermark` 文件夹：用于 **5.0 版本移除水印**
- `DmitriRender-retime.bat`：**用于重置 3.0 版本的试用时间**
- **3.0 版本兼容 GPU 系列**：
  - AMD RX 5700 系列  
  - NVIDIA GTX 16XX 系列  
  - NVIDIA Maxwell / Pascal 架构显卡
  - NVIDIA RTX 2000 系列
  - Universal (RTX30) 驱动支持显卡

---

### ⚠️ 使用须知

我**并非这些补丁或工具的开发者**，但是整理与汇整资料方便大家使用。

部分补丁使用 **Jongan DLL 劫持技术（DLL Hijacking）**，可能被防毒软件误认为可疑文件。请根据个人情況自行判断是否使用，并建议在干净的测试环境下操作。

---

🕒 最后更新：2025年6月

---

## 🇺🇸 English Version

### 🔹 Software Overview

**DmitriRender** is a real-time video frame interpolation filter based on the DirectShow framework, developed by Dmitri Zdorov. It inserts intermediate frames to increase the video framerate to 60fps or higher for smoother playback.

Known for its simplicity and low resource usage, it was a popular choice for HFR enthusiasts and home theater users, working with MPC-HC, PotPlayer, and other DirectShow-compatible players.

---

### 🔹 Development Status

**DmitriRender is no longer under development**, and the **official website is no longer accessible**. The final version was closed-source and has no ongoing community support. Compatibility issues may arise over time.

---

### 🔹 Included Files & Notes

- `dmitriRender_3.0.0.1.exe`: **Installer for version 3.0 (stable)**
- `dmitriRender_5.0.0.1_beta1.zip`: **Beta version 5.0 installer (ZIP archive)**
- `Watermark` folder: **For removing watermark in version 5.0**
- `DmitriRender-retime.bat`: **Used to reset trial period for version 3.0**
- **Version 3.0 compatible with the following GPU series**:
  - AMD RX 5700 series  
  - NVIDIA GTX 16XX series  
  - NVIDIA Maxwell / Pascal GPUs  
  - NVIDIA RTX 2000 series  
  - GPUs supported by Universal driver

---

### ⚠️ Disclaimer

I am **not the developer** of these patches or tools — just a **collector and documenter** compiling this for reference.

Some patches use **Jongan DLL hijacking**, which may trigger antivirus software. Please evaluate and use at your own discretion, preferably in a secure test environment.

---

🕒 Last Updated: June 2025
