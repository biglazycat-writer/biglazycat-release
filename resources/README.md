# 可选资源

安装包不包含这些文件。桌面端可以在「设置 → 本地模型与字体」里下载到本机数据目录，也可以自己把文件放到对应文件夹。

| 目录 | 用途 | 放到本机 |
|---|---|---|
| `typesetting/` | PDF 排版用的 Noto Serif SC，以及 Typst、PDFium 的 wasm。这个目录里还可以再放别的 `.ttf` / `.otf`，导出 PDF 时选用。 | `<数据目录>/models/typesetting/` |
| `ocr-models/` | 本地 OCR 的检测模型、识别模型和配套字表 | `<数据目录>/models/ocr-models/` |
| `bergamot-models/` | 本地中英翻译模型。`registry.json` 点名的文件都要在 | `<数据目录>/models/bergamot-models/` |

`manifest.json` 记录每个文件的大小和 SHA-256。

GitHub 根地址：https://raw.githubusercontent.com/biglazycat-writer/biglazycat-release/main/resources/

Gitee 根地址：https://gitee.com/biglazycatwriter/blc-release/raw/master/resources/

同一相对路径两边都有。GitHub 不可用时改用 Gitee。
