# laleoarrow R-Universe

[![](https://laleoarrow.r-universe.dev/badges/:registry)](https://laleoarrow.r-universe.dev)
[![](https://laleoarrow.r-universe.dev/badges/:total)](https://laleoarrow.r-universe.dev)

> Personal R package universe for Layered Exploratory Omics (LEO) ecosystem

## 📦 Quick Installation

Set up the laleoarrow r-universe repository to easily install all LEO packages and their dependencies:

```r
# Configure repository
options(repos = c(
  laleoarrow = 'https://laleoarrow.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'
))

# Install any LEO package
install.packages('leo.gwas')   # GWAS analysis tools
install.packages('leo.basic')  # Core utilities  
install.packages('leo.sc')     # Single-cell analysis tools
```

**All dependencies will be automatically installed**, including GitHub-only packages like `annotables`, `MRlap`, and `TwoSampleMR`!

## 🎯 Why Use This R-Universe?

- ✅ **One-step installation**: No need to manually install GitHub dependencies
- ✅ **Pre-built binaries**: Faster installation (no compilation needed)
- ✅ **Automatic updates**: Use `update.packages()` to get the latest versions
- ✅ **Version tested**: All packages are built and tested together

## 📚 Available Packages

| Package | Version | Description |
|---------|---------|-------------|
| [**leo.basic**](https://github.com/laleoarrow/leo.basic) | [![](https://laleoarrow.r-universe.dev/badges/leo.basic)](https://laleoarrow.r-universe.dev/leo.basic) | Core utilities for LEO packages |
| [**leo.gwas**](https://github.com/laleoarrow/leo.gwas) | [![](https://laleoarrow.r-universe.dev/badges/leo.gwas)](https://laleoarrow.r-universe.dev/leo.gwas) | GWAS analysis and visualization tools |
| [**leo.sc**](https://github.com/laleoarrow/leo.sc) | [![](https://laleoarrow.r-universe.dev/badges/leo.sc)](https://laleoarrow.r-universe.dev/leo.sc) | Single-cell RNA-seq analysis utilities |
| [**annotables**](https://github.com/stephenturner/annotables) | [![](https://laleoarrow.r-universe.dev/badges/annotables)](https://laleoarrow.r-universe.dev/annotables) | Gene annotation data (dependency) |
| [**MRlap**](https://github.com/n-mounier/MRlap) | [![](https://laleoarrow.r-universe.dev/badges/MRlap)](https://laleoarrow.r-universe.dev/MRlap) | Mendelian Randomization (dependency) |
| [**TwoSampleMR**](https://github.com/MRCIEU/TwoSampleMR) | [![](https://laleoarrow.r-universe.dev/badges/TwoSampleMR)](https://laleoarrow.r-universe.dev/TwoSampleMR) | Two-sample MR methods (dependency) |

## 🚀 Permanent Setup (Recommended)

Add this to your `~/.Rprofile` to permanently enable the laleoarrow universe:

```r
# Edit ~/.Rprofile
options(repos = c(
  laleoarrow = 'https://laleoarrow.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'
))
```

After this setup, you can install any package with just:
```r
install.packages('leo.gwas')
```

## 📖 Documentation

- **Package Dashboard**: [laleoarrow.r-universe.dev](https://laleoarrow.r-universe.dev)
- **Build Status**: [GitHub Actions](https://github.com/r-universe/laleoarrow/actions)
- **Main Package**: [leo.gwas](https://laleoarrow.github.io/leo.gwas/)

## 👨‍💻 About

This r-universe is maintained by [Ao Lu](https://github.com/laleoarrow) and hosts the **Layered Exploratory Omics (LEO)** package ecosystem for genomic data analysis.

**Contact**: [luao@stu.cqmu.edu.cn](mailto:luao@stu.cqmu.edu.cn)

---

*Powered by [r-universe.dev](https://r-universe.dev) 🌌*
