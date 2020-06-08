简体中文 | [English](./README.md)

# SCU-Beamer-Template

四川大学的非官方 Beamer 模板。该模板修改自 [beamer_nankai](https://github.com/zshicode/LaTeX-Beamer-Nankai/tree/master/beamer_nankai).

## 文件

- `SCUBeamer.sty`: 主题文件。你可以修改其中一些设置。例如：主题色、背景图片、字体大小、一些 box 的宽度和高度等。
- `demo.tex`: 示例文件。
- `references.bib`: bibtex 参考文献文件。
- `figures/`: 图片文件夹。

## 用法

使用下方命令来编译生成 PDF：

```bash
xelatex demo
biber demo
xelatex demo
xelatex demo
```

## 维护者

[@ShaneTian](https://github.com/ShaneTian).

## 使用许可

[Apache License 2.0](LICENSE) © ShaneTian