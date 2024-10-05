# ColorNote
帮助记忆颜色搭配的笔记
此项目是一个基于 Kivy 框架实现的颜色选择器应用，用户可以通过滑动颜色条来选择不同的颜色并显示出来。

## 功能
- 用户可以通过 RGB 三个滑动条来选择颜色。
- 实时预览选择的颜色。
- 显示所选颜色的 RGB 值。

## 依赖项

要运行此项目，你需要安装以下依赖项：

- Python 3.x
- Kivy (用于创建 GUI)
- Pillow (用于图像处理)

你可以使用以下命令来安装这些依赖项：

```bash
pip install kivy Pillow
```

## 文件说明

- `kivy_color_picker.py`：该文件包含了实现颜色选择器的主要逻辑。
- `main.py`：项目的入口文件，初始化 Kivy 应用程序并调用颜色选择器功能。

## 运行方法

1. 首先，确保已经安装所需的依赖项。
2. 运行 `main.py` 文件启动应用程序。

```bash
python main.py
```

## 使用指南

- 打开应用程序后，将显示颜色选择界面。
- 使用 RGB 三个滑动条调整颜色值，选择你想要的颜色。
- 应用程序会实时显示你选择的颜色，并且在界面上更新对应的 RGB 值。

## 开发者

- HPEL
- 3527206832@qq.com
