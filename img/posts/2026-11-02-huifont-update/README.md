# MyNote 配图字体更新 · 2026-11-02

用户选择 A：HuiFontP29 / ふい字Ｐ v2.9 作为默认配图字体，并授权更新此前生成且正在博客引用的六张图。
五张概念漫画与一张报告流程图的构图和语义沿用原图；原文件保留。

- 根目录六张 PNG 为公开使用的成品，`assets.json` 记录来源、用途、哈希、尺寸与必要换词。
- `backgrounds/` 是原生图像工具从旧图制作的无字底图，`prompts/` 保存实际编辑提示词。
- `typesetting.json` 保存文字及坐标；`typography-report.json` 记录实际字体加载、字形轮廓及排版检查。
- 字体文件由用户提供，未将字体二进制或含字体数据的 HTML 再分发。
- 复现：在博客仓库按 `docs/illustration-typography.md` 配置同版字体，运行
  `python scripts/illustration-typography.py render <本目录>/typesetting.json <输出目录>`。

已目视复核全部成品与底图：无账户、持仓、订阅者数据、真实报告截图或第三方标识；PNG 无额外 EXIF、定位和私人注释。
流程图仍为五步、四条向右连接；格式校验和事实核验的区别、定时运行的限制均保留。
