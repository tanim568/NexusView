# NexusView 🌐🎬

[![PyPI version](https://img.shields.io/pypi/v/NexusView.svg)](https://pypi.org/project/NexusView/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Versions](https://img.shields.io/pypi/pyversions/NexusView.svg)](https://pypi.org/project/NexusView/)

**NexusView** is a lightweight, easy-to-use Python package that allows you to seamlessly render live websites and YouTube videos directly inside your Jupyter Notebooks (`.ipynb`).

Whether you are building interactive educational materials, documenting research with live references, or just want to stop switching tabs while coding, NexusView brings the web directly to your cell output.

## ✨ Features

- **Embed Live Websites:** Render fully interactive web pages inside your notebook.
- **Play YouTube Videos:** Embed and play YouTube videos without leaving your workspace.
- **Customizable Dimensions:** Easily adjust the width and height of your rendered views to fit your screen.
- **Lightweight:** Built specifically for Jupyter environments with minimal dependencies.

## 📦 Installation

You can install NexusView easily via pip:

```bash
pip install NexusView
```

## How to install this package in your system

```bash
 conda create -n nexusview_env python=3.8 -y
```

```bash
 conda activate nexusview_env
```

```bash
pip install -r requirements_dev.txt
```

## 🚀 Usage

Using NexusView is incredibly straightforward. Import the package and call the render functions in your Jupyter Notebook cells.

### 1\. Rendering a Website

To display a live website, use the website rendering function and pass the URL. You can optionally set the width and height.

```python
from nexusview import render_website

# Render a webpage with default dimensions
render_website("[https://en.wikipedia.org/wiki/Machine_learning](https://en.wikipedia.org/wiki/Machine_learning)")

# Render a webpage with custom dimensions
render_website("[https://python.org](https://python.org)", width=1000, height=600)
```

### 2\. Rendering a YouTube Video

To embed a YouTube video, simply pass the video URL or the Video ID.

```python
from nexusview import render_youtube

# Render using a full YouTube URL
render_youtube("[https://www.youtube.com/watch?v=dQw4w9WgXcQ](https://www.youtube.com/watch?v=dQw4w9WgXcQ)")

# Or render using just the Video ID, with custom dimensions
render_youtube("dQw4w9WgXcQ", width=800, height=450)
```

## 🛠️ Dependencies

- Python 3.6+
- Jupyter Notebook / JupyterLab
- `IPython` (Core dependency for rendering outputs)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome\!
Feel free to check out the [issues page](https://www.google.com/search?q=https://github.com/YOUR_GITHUB_USERNAME/NexusView/issues) if you want to contribute.

1.  Fork the repository
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

_Built with ❤️ for the Jupyter community._
