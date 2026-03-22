# Daniel Jimmy's Personal Homepage

Welcome to my personal academic website repository! This site is built with [Academic Pages](https://academicpages.github.io/), a GitHub Pages template designed for academics and researchers.

## 👋 About Me

I'm a master's student at the [College of Information Science and Electronic Engineering](https://www.isee.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/). My research focuses on:

- **Computer Vision**: Image recognition, object detection, and visual understanding
- **Multimodal Learning**: Vision-language models and cross-modal learning
- **Large Language Models**: Training and fine-tuning large-scale deep learning models
- **Deep Learning**: Developing efficient training methods for large datasets

### 🎓 Education

- **M.S.** in Information Science and Electronic Engineering, Zhejiang University (2024-present)
- **B.S.** in Electronic Information Engineering, Jilin University (2023)

### 🔧 Technical Skills

- **Programming**: Python, C++, MATLAB
- **Deep Learning**: PyTorch, TensorFlow, Keras
- **Computer Vision**: OpenCV, PIL, Image Processing
- **Tools**: Git, Docker, Linux, Jupyter

## 🌐 Visit My Website

Check out my full academic profile at: **[https://Jim3503.github.io](https://Jim3503.github.io)**

### Quick Links:
- **About**: [https://Jim3503.github.io/about/](https://Jim3503.github.io/about/)
- **CV**: [https://Jim3503.github.io/cv/](https://Jim3503.github.io/cv/)
- **Publications**: [https://Jim3503.github.io/publications/](https://Jim3503.github.io/publications/)
- **GitHub**: [https://github.com/Jim3503](https://github.com/Jim3503)

## 📧 Contact

Feel free to reach out via email: [ming.ji@zju.edu.cn](mailto:ming.ji@zju.edu.cn)

---

## Repository Information

This repository contains the source code for my personal academic website. It's built using Jekyll and hosted on GitHub Pages.

## Running locally

To preview changes locally before pushing to GitHub:

1. Clone the repository
1. Install dependencies (ruby-dev, bundler, nodejs):
    ```bash
    # Linux/WSL
    sudo apt install ruby-dev ruby-bundler nodejs

    # macOS
    brew install ruby node
    gem install bundler
    ```
1. Install Ruby dependencies:
    ```bash
    bundle install
    ```
1. Start the local server:
    ```bash
    bundle exec jekyll serve -l -H localhost
    ```
   The site will be available at `http://localhost:4000`

For Linux users, you may need: `sudo apt install build-essential gcc make`

## Using Docker

Alternatively, you can use Docker to avoid installing dependencies:

```bash
# Build the container
docker build -t jekyll-site .

# Run the container
docker run -p 4000:4000 --rm -v $(pwd):/usr/src/app jekyll-site
```

## License

This site is built using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) by Michael Rose and released under the MIT License.
