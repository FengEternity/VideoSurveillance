# VideoSurveillance

## 项目简介

VideoSurveillance 是一个简单的视频监控系统示例，使用C++、OpenCV和Qt6进行开发。该项目展示了如何捕获视频帧并在用户界面中实时显示。

## 目录结构

```
VideoSurveillance/
├── CMakeLists.txt
├── src/
│   ├── main.cpp
│   ├── video_capture.cpp
│   ├── video_capture.h
│   ├── main_window.cpp
│   ├── main_window.h
│   └── main_window.ui
├── include/
│   └── ...
├── resources/
│   └── ...
└── tests/
    └── ...
```

## 依赖

- [Qt6](https://www.qt.io/download)
- [OpenCV](https://opencv.org/releases/)

## 编译和运行

### 1. 克隆仓库

```bash
git clone https://github.com/FengEternity/VideoSurveillance.git
cd VideoSurveillance
```

### 2. 创建构建目录并进入

```bash
mkdir build
cd build
```

### 3. 运行CMake配置

```bash
cmake ..
```

### 4. 编译项目

```bash
make
```

### 5. 运行可执行文件

```bash
./VideoSurveillance
```

## 项目文件说明

- `CMakeLists.txt`：CMake配置文件，用于构建项目。
- `src/main.cpp`：程序入口，初始化Qt应用并显示主窗口。
- `src/video_capture.h` 和 `src/video_capture.cpp`：封装视频捕获逻辑的类。
- `src/main_window.h` 和 `src/main_window.cpp`：主窗口类，包含视频显示逻辑。
- `src/main_window.ui`：使用Qt Designer设计的UI文件。

## 贡献

欢迎贡献代码！请提交Pull Request或报告问题。

## 许可证

该项目使用MIT许可证，详见 [LICENSE](LICENSE) 文件。
