# Payment Security Research Documentation

This directory contains the comprehensive documentation for the CVV Security Research project, built with Sphinx and deployed to both Read the Docs and GitHub Pages.

## 📚 Documentation Overview

The documentation provides detailed coverage of:
- **Thesis Research**: Complete thesis sections with academic citations
- **Security Analysis**: In-depth CVV validation vulnerability research
- **PCI DSS Compliance**: Comprehensive compliance gap analysis
- **Research Papers**: Systematic review of 20+ academic papers
- **Implementation Guides**: Practical security frameworks and code examples

## 🚀 Quick Start

### Local Development

1. **Install dependencies**:
   ```bash
   pip install -r source/requirements.txt
   ```

2. **Build documentation**:
   ```bash
   make html
   ```

3. **View locally**:
   ```bash
   open build/html/index.html
   ```

## 🌐 Deployment Options

### Read the Docs (Recommended)

1. **Connect Repository**:
   - Go to [Read the Docs](https://readthedocs.org)
   - Sign in with GitHub
   - Import your repository: `cswasif/cvv-security-research`

2. **Automatic Configuration**:
   - The `.readthedocs.yml` file is already configured
   - Documentation will build automatically on every push to `main`

### GitHub Pages

GitHub Pages is automatically configured via GitHub Actions:

1. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Set source to "GitHub Actions"

2. **Automatic Deployment**:
   - Every push to `main` branch triggers automatic deployment
   - Documentation available at: `https://cswasif.github.io/cvv-security-research`

## 📁 Directory Structure

```
docs/
├── source/
│   ├── conf.py              # Sphinx configuration
│   ├── index.rst            # Main documentation index
│   ├── requirements.txt     # Python dependencies
│   ├── thesis/              # Thesis documentation
│   ├── papers/              # Research papers analysis
│   └── citation-database.rst
├── build/                   # Generated HTML
└── Makefile                 # Sphinx build commands
```