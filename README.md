# 图片加水印工具📷

这是一款简单易用的图片加水印工具，可以帮助用户在图片上添加自定义的水印文字。用户只需将图片文件拖放到工具界面中，就可以自动加载图片，并在预览区域显示。在输入框中输入水印文字后，工具会实时在预览图上添加水印，并支持导出加水印后的图片，支持 PNG、JPEG、BMP 和 GIF 四种格式。未来，工具还将支持拖放多个文件，实现批量处理功能，方便用户快速地处理多张图片。

该图片加水印工具实现了以下功能：

1. **拖放图片：** 将图片拖到窗口中，自动加载图片，并在预览区域显示。
2. **添加水印：** 在预览图上添加水印文字，支持实时预览。
3. **导出图片：** 将加水印后的图片导出为 PNG、JPEG、BMP 或 GIF 格式。

## 技术要点

1. 使用 `Tkinter` 模块创建 GUI 界面。
2. 使用 `Pillow` 模块处理图片，包括加载图片、添加水印、导出图片等操作。
3. 使用 `windnd` 模块实现拖放文件功能。
4. 使用 `trace` 方法监听水印文字输入框的变化，实现实时预览。
5. 使用 `filedialog` 模块实现文件保存对话框。

# 快速开始

1. 安装 ``Python 3.8``，搭建相关开发环境.
2. 执行 ``pip install tkinter``，``pip install pillow``，``pip install windnd``等，安装库。
3. 执行 ``python main.py``，运行Python程序。
4. 执行 ``pyinstaller -F -w main.py``将程序打包，双击 ``exe``文件即可运行程序。

## 优化方向参考

1. 增加水印位置、颜色、字体、字号、透明度等参数的设置。
2. 预置黑白红，三种水印颜色，用户可以直接选择，默认是黑色。
3. 增加批量处理功能，支持拖放多个文件，一次性添加水印到多张图片中。
4. 增加图片裁剪、缩放等功能，提高图片处理的灵活性。
5. 优化 GUI 界面，提高用户体验。
6. 支持撤销操作，方便用户修改水印内容。
7. 水印过长则自动换行，文字不要超出图片外。

# 联系我们

- 本程序基于 [MIT](https://opensource.org/licenses/MIT) 许可证开源。
- 本程序不定时更新，如果大家在使用的过程中，发现任何bug或有不错的想法，欢迎提出交流。
- 源代码：[https://github.com/wowqaqtat/Image-watermark-tool](https://github.com/wowqaqtat/Image-watermark-tool)
- 视频讲解：bilibili
- 邮箱：[help@haodukeji.cn](mailto:help@haodukeji.cn)
