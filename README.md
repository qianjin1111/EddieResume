# EddieResume

📄 **Markdown 简历 + GitHub Actions 自动生成 PDF/HTML**

在线预览 → [qianjin1111.github.io/EddieResume](https://qianjin1111.github.io/EddieResume)

---

## 工作流

```
resume.md ──(GitHub Actions)──→ index.html ──→ GitHub Pages
                              ──→ resume.pdf  ──→ Release
```

每次 push 到 `main` 分支自动触发。

## 本地构建

```bash
# 安装依赖
brew install pandoc wkhtmltopdf  # macOS
# 或 sudo apt-get install pandoc wkhtmltopdf  # Linux

# 生成 HTML
pandoc resume.md --standalone --css=style.css -o index.html

# 生成 PDF
pandoc resume.md --pdf-engine=wkhtmltopdf --css=style.css -o resume.pdf
```

## 目录

```
├── resume.md              # 简历源文件（Markdown）
├── style.css              # HTML/PDF 样式
├── .github/workflows/
│   └── build.yml          # 自动构建 + 部署
└── README.md
```
