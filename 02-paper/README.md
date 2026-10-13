# 课程论文 · UESTC

1. 将整个文件夹上传至 Overleaf，主文档选择 `main.tex`，编译器选择 **XeLaTeX**。
2. 本地安装完整 TeX Live / MacTeX 后，在本目录运行 `latexmk -xelatex main.tex`；或运行两次 `xelatex main.tex`。
3. 在 `main.tex` 的 `uestcsetup` 中修改个人信息，在 `begin{document}` 后替换示例正文。

校徽沿用原项目 `report_template3/logo.pdf`；银杏叶为 TikZ 绘制。此为社区模板，不是学校官方格式要求。提交前检查学院或课程规定。

支持数学公式、三线表、图片、代码和交叉引用。示例参考文献采用内置 `thebibliography`，无需额外文献编译工具。
