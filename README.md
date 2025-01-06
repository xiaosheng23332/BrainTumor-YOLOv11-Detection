# BrainTumor-YOLOv11-Detection

[English](#english) | [中文](#chinese)

## English
A comprehensive brain tumor detection system based on YOLOv11 models, providing desktop and web interfaces for medical image analysis. Features include real-time detection through images, videos and webcam streams using PyQt5 for desktop GUI and Flask+Socket.IO for web interface. Implements C3TR attention mechanism for enhanced detection accuracy.

## Chinese
基于YOLOv11的综合脑肿瘤检测系统提供了医学图像处理的完整解决方案。本项目实现了桌面端和Web端双界面，并集成了实时摄像头检测功能。系统核心采用改进的YOLOv11模型，引入C3TR注意力机制提升检测精度。

## Features | 功能特性

- 🖥️ Desktop Application (PyQt5) | 桌面应用
- 🌐 Web Interface (Flask+Socket.IO) | Web界面
- 📷 Real-time Camera Detection | 实时摄像头检测
- 🎥 Video File Detection | 视频文件检测
- 🖼️ Image File Detection | 图片文件检测
- 📊 Result Visualization | 结果可视化

## Requirements | 环境要求

- Windows 10/11
- Python 3.10
- CUDA 11.8+
- cuDNN 8.9.0

## Installation | 安装说明

1. Clone the repository | 克隆仓库
```bash
git clone https://github.com/yourusername/BrainTumor-YOLOv11-Detection.git
cd BrainTumor-YOLOv11-Detection
```

2. Create virtual environment | 创建虚拟环境
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Install dependencies | 安装依赖
```bash
pip install -r requirements.txt
```

## Usage | 使用说明

### Desktop Application | 桌面应用
```bash
python src/desktop/main.py
```

### Web Application | Web应用
```bash
python src/web/app.py
```

## Tech Stack | 技术栈

- Python 3.10
- PyTorch 2.1.0
- YOLOv11
- PyQt5
- Flask
- OpenCV

## License | 许可证

This project is licensed under the MIT License - see the LICENSE file for details.

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。
```
