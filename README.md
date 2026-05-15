<div align="center">
<img src="docs/logo.gif" width="160" height="160" alt="瞾 — Shuo Zhao" style="border-radius:50%;"/>



# Aut_Sci_PPt

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

---

<a id="english"></a>

**Aut_Sci_PPt** is an automated agent designed to convert academic papers (PDF) or structured text into professional, presentation-ready PowerPoint files (.pptx). It is specifically optimized for graduate defense, academic seminars, and research proposals.

## ✨ Key Features

- 📄 **PDF Extraction**: Intelligent parsing of academic papers using PyMuPDF.
- 📐 **Smart Layout**: Automatic typography engine that prevents overflow and maintains white space.
- ➗ **LaTeX Support**: Renders complex formulas as high-definition transparent PNGs.
- 🖼️ **HD Figures**: Extracts and embeds figures with high DPI for clarity.
- 🎨 **Academic Theme**: Built-in professional theme following common university standards (Deep Blue & Accent Red).

## 🚀 Quick Start

### Installation

```bash
pip install python-pptx pyyaml pymupdf Pillow
```

### Basic Usage

```python
from aut_sci_ppt import PPTAgent

agent = PPTAgent()
user_input = """
主题：材料学科研究生推免汇报
申请人：dd
1. 教育背景
- dd大学
- 绩点: 3.61/5.0
"""
agent.generate(user_input, "presentation.pptx")
```

## 🤝 Contributing

This project is open-sourced to help students and researchers. Feel free to submit issues or pull requests to improve the layout engine and parsing accuracy.

---


## 📄 License

MIT License — see [LICENSE](LICENSE)



## Star History

<a href="https://www.star-history.com/?repos=ShZhao27208%2FAut_Sci_ppt&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ShZhao27208/Aut_Sci_ppt&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ShZhao27208/Aut_Sci_ppt&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ShZhao27208/Aut_Sci_ppt&type=date&legend=top-left" />
 </picture>
</a>
