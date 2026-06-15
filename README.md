# EddieResume

📄 **Markdown 简历 + GitHub Actions 自动生成 PDF/HTML**

在线预览 → [qianjin1111.github.io/EddieResume](https://qianjin1111.github.io/EddieResume)

下载 PDF → [📄 resume.pdf（最新版）](https://github.com/qianjin1111/EddieResume/releases/latest/download/resume.pdf)

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
brew install pandoc weasyprint  # macOS
# 或 sudo apt-get install pandoc weasyprint  # Linux（或 pip install weasyprint）

# 生成 HTML
pandoc resume.md --standalone --css=style.css -o index.html

# 生成 PDF（使用 WeasyPrint，分页更干净、不会出现大片留白）
pandoc resume.md --pdf-engine=weasyprint --css=style.css -o resume.pdf
```

## 目录

```
├── resume.md              # 简历源文件（Markdown）
├── style.css              # HTML/PDF 样式
├── .github/workflows/
│   └── build.yml          # 自动构建 + 部署
└── README.md
```
