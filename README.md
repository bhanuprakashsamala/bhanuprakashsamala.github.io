# Bhanu Prakash Samala - CFD Portfolio

This repository contains the source code for my personal portfolio website showcasing my work in Computational Fluid Dynamics (CFD), numerical methods, and high-performance computing.

## Getting Started with GitHub Pages

### 1. Setting Up Your Repository

1. Create a new repository on GitHub named `yourusername.github.io`
2. Clone this repository locally:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```
3. Copy all the files from this portfolio template into your repository

### 2. Customizing Your Portfolio

1. Replace placeholder text and images with your own content
2. Update the profile information in `index.html`
3. Add your own projects in the projects section
4. Customize the CSS in `css/style.css` if needed

### 3. Adding Your Research and Work

1. Create detailed project pages in the `projects/` directory
2. Add your publications to the publications section
3. Include images of your CFD work in the `images/` directory

### 4. Publishing Your Site

1. Commit your changes:
   ```bash
   git add .
   git commit -m "Initial portfolio setup"
   git push -u origin main
   ```
2. Your site will be available at `https://yourusername.github.io`

## Folder Structure

```
.
├── css/
│   └── style.css             # Main stylesheet
├── images/                   # Image assets
│   ├── profile.jpg
│   ├── project1.jpg
│   └── ...
├── js/
│   └── main.js               # JavaScript functionality
├── projects/                 # Individual project pages
│   ├── vortex-validation.html
│   └── ...
├── research/                 # Detailed research pages
│   ├── vortex-method.html
│   └── ...
├── docs/                     # PDF documents and presentations
├── index.html                # Main portfolio page
└── README.md                 # This file
```

## Adding Interactive Notebooks

To add interactive code demonstration via Jupyter notebooks:

1. Create your Jupyter notebooks in a separate repository
2. Use GitHub's nbviewer service to render them
3. Link to the notebooks from your portfolio

Example for linking to a notebook:

```html
<a href="https://nbviewer.jupyter.org/github/yourusername/cfd-notebooks/blob/main/vortex_method.ipynb" target="_blank">
  View Interactive Notebook
</a>
```

For more advanced interactive experiences, consider:

1. **Binder**: Turn your repositories into interactive environments
   ```
   https://mybinder.org/v2/gh/yourusername/cfd-notebooks/main?filepath=vortex_method.ipynb
   ```

2. **Google Colab**: Share notebooks that run on Google's infrastructure
   ```
   https://colab.research.google.com/github/yourusername/cfd-notebooks/blob/main/vortex_method.ipynb
   ```

## Customization Tips

1. **Adding syntax highlighting**: Include Prism.js for code snippets
2. **LaTeX equations**: Use MathJax for mathematical content
3. **Custom domain**: Set up a custom domain in GitHub Pages settings
4. **Analytics**: Add Google Analytics to track site visitors

## License

This template is available under the MIT License. Feel free to modify and use it for your own portfolio.
