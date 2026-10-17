# 星月夜 · 自由空间

自由探索的三维星空、村庄与麦田。包含分区卷云、移动云影、间歇麦浪和萤火虫。

2026-10-17 更新：默认自由探索，移动速度 24 m/s；可选 1 分 22 秒自动漫游，从原画视角经过麦田与教堂，后退拉远后沿村庄上空弧线回到原画视角，途中连续移动，萤火虫在画面两侧伴飞，可暂停、拖动进度或随时接管。局部深蓝色调浅，天空保留分层流动。

此前更新：起伏的立体星云及外层云团；更柔和的蓝白云带与山村光影；麦田高低错落，近景麦穗包含独立麦粒、芒须和叶片；萤火虫沿更大范围的平滑轨迹飞行；手机竖屏显示可关闭的横屏提示，并提供横屏触控布局。

[在线体验](https://wangjw328.github.io/starn/)

`index.html` 是完整的单文件发布版本，Three.js、样式和笔触数据全部内嵌，不需要 CDN 或额外资源。

完整可编辑源码与构建配置见 `starry-night-source.zip`。解压后执行：

```sh
npm install
npm run check
npm run build
npm run dev
```

本地访问 http://127.0.0.1:8797/ 。WASD 飞行、Q/E 升降、Shift 加速、鼠标拖动环顾、滚轮穿行，1—7 切换地点，R 返回起点。

GitHub Pages 使用 main 分支的根目录发布。

源码修改后运行 `node tools/package-github.mjs` 与 `python tools/package-source.py`，将 `github-upload/index.html` 和源码压缩包上传到仓库根目录即可更新。

以梵高 1889 年《星月夜》为灵感独立重建，不是原视频作者源码。图像为公有领域，来自 [Wikimedia Commons / Google Art Project](https://commons.wikimedia.org/wiki/File:Van_Gogh_-_Starry_Night_-_Google_Art_Project.jpg)。Three.js 为 MIT 许可，见 `THREE-LICENSE.txt`。动画采用程序化近似，性能依设备而异。
