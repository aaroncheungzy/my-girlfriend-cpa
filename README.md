# 我的女友 CPA

一篇把中国注册会计师考试拟人化的怨恨文，以 5 × 8 英寸小册子形式排版。

## 内容

- 全文 21 节，围绕会计、审计、财管、税法、经济法和战略展开。
- 保留可复现的 XeLaTeX 源码与开源中文字体。
- 参考 [HEJustinSun/my-girlfriend-jingtian-latex](https://github.com/HEJustinSun/my-girlfriend-jingtian-latex) 的书册排版工程组织方式；正文与封面为本项目内容。

## 编译

需要 XeLaTeX（推荐 TeX Live）：

```bash
mkdir -p build
xelatex -interaction=nonstopmode -halt-on-error -output-directory=build main.tex
xelatex -interaction=nonstopmode -halt-on-error -output-directory=build main.tex
```

生成文件为 `build/main.pdf`。

