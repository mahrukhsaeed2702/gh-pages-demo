# 🌐 GitHub Pages Demo

A simple static website that is automatically deployed to **GitHub Pages** using **GitHub Actions**.

🔗 **Visit WebSite:**  
👉 [mahrukhsaeed2702.github.io/gh-pages-demo](https://mahrukhsaeed2702.github.io/gh-pages-demo/)

---

## 🚀 Key Highlights

- 📄 Static website using **HTML** and **CSS**
- 🤖 Automated deployment with **GitHub Actions**
- 📱 Clean and responsive design
- ⚡ Fast and lightweight

---

## 📁 Project Structure
gh-pages-demo/
├── src/
│ ├── index.html # Main HTML file
│ └── style.css # Stylesheet
├── .github/
│ └── workflows/
│ └── deploy.yml # GitHub Actions workflow for deployment
└── README.md # This file

## 🛠️ Deployment Automation

The deployment is handled by a GitHub Actions workflow (`deploy.yml`), which:

- Checks out the code
- Copies contents of `src/` to a temporary directory
- Pushes it to the `gh-pages` branch

