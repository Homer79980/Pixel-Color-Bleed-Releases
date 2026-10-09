# Pixel Color Bleed

Pixel Color Bleed 是一款 Adobe Photoshop 插件，用于沿透明图像的真实轮廓和局部颜色走势生成外扩像素，内部实心、最外缘圆润抗锯齿，减少缩放、滤波和图集采样产生的边缘污染。处理结果会创建在原图层下方，原图层保持不变。

## 下载

当前版本：`0.1.5`

- [下载最新版](https://github.com/Homer79980/Pixel-Color-Bleed-Releases/releases/latest)
- [直接下载 0.1.5 插件包](https://github.com/Homer79980/Pixel-Color-Bleed-Releases/releases/download/v0.1.5/pixel-color-bleed-0.1.5.ccx)
- Photoshop 版本要求：23.0 或更高版本
- 文档要求：RGB 模式，并选择带透明区域的图像图层

## 安装与使用

1. 从 Latest Release 下载 `pixel-color-bleed-0.1.5.ccx`。
2. 双击 CCX，并通过 Creative Cloud 完成安装。
3. 重启 Photoshop，从“插件”菜单打开“颜色像素扩散”。
4. 选择一个带透明区域的 RGB 图像图层，设置参数后执行生成。

## 参数

- 扩展像素：向外扩展的像素半径。
- 色相：`-180` 到 `180`。
- 饱和度：`-100` 到 `100`。
- 明度：`-100` 到 `100`。
- 自动扩展画布：文档边界会裁切结果时开启。

色相、饱和度和明度只作用于新生成的外扩像素，每项均支持滑块和数值输入。

## 0.1.5 更新

- 保持不同色块主体清晰，只在交界附近做窄幅、细腻的抗锯齿过渡。
- 交界过渡只处理一次，减少宽范围混色，同时柔化硬边。
- 保留连续滑块调节与数值输入。
- 保留圆润外轮廓抗锯齿，原图层和封闭孔洞保持不变。

## 历史版本

- [0.1.5](https://github.com/Homer79980/Pixel-Color-Bleed-Releases/releases/tag/v0.1.5)：色块交界窄幅抗锯齿，让分界清晰、过渡细腻。
- [0.1.3](https://github.com/Homer79980/Pixel-Color-Bleed-Releases/releases/tag/v0.1.3)：滑块拖动修复与圆润轮廓抗锯齿优化。
- [0.1.1](https://github.com/Homer79980/Pixel-Color-Bleed-Releases/releases/tag/v0.1.1)：修复部分 Photoshop 环境中的滑块初始化和拖动问题。
- [0.1.0](https://github.com/Homer79980/Pixel-Color-Bleed-Releases/releases/tag/v0.1.0)：首个公开版本。
