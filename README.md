English | [简体中文](./README_zh.md)

# SCU-Beamer-Template

An unofficial beamer template of Sichuan University.

This template is based on [beamer_nankai](https://github.com/zshicode/LaTeX-Beamer-Nankai/tree/master/beamer_nankai).

## Files

- `SCUBeamer.sty`: The style file. You can change some of these settings. For example: theme color, background picture, font size, width and height of some boxes, etc.
- `demo.tex`: The example file.
- `references.bib`: The bibtex reference file.
- `figures/`: The figures floder.

## Usage

To compile the beamer, use:

```bash
xelatex demo
biber demo
xelatex demo
xelatex demo
```

## Maintainers

[@ShaneTian](https://github.com/ShaneTian).

## License

[Apache License 2.0](LICENSE) © ShaneTian