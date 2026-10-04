# 第一次测试 6 题解题报告（LaTeX）

编译（中文必须用 xelatex，编两遍目录才准）：

```bash
cd ~/tjurm2027-test1/report
xelatex main.tex && xelatex main.tex
```

产物 `main.pdf` 会一起提交到仓库，方便直接阅读。

- 写作纪律：每题四小节 —— 题目 / 思路 / 代码 / 结果
- 图片取自仓库的 `../images/`，代码取自 `../src/tests.cpp`（改代码后重新编译即同步）
- 中间文件（`.aux .log .toc .out`）已由 `.gitignore` 忽略，**PDF 会提交**
