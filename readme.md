# VSCode R Snippets Collection

![R Language](https://img.shields.io/badge/R-v4.3%2B-blue)
![Tidyverse](https://img.shields.io/badge/Tidyverse-Latest-blue)
![VSCode](https://img.shields.io/badge/VSCode-Compatible-brightgreen)
![License](https://img.shields.io/badge/license-Beerware-yellow)

## Overview

A professional collection of VSCode snippets for R and R Markdown, designed to accelerate your data science workflow. Supports the latest R 4.5.0 features and works with VS Code, [Positron](https://github.com/posit-dev/positron), and other modern R IDEs.

> **Pro Tip**: These snippets also work in the new RStudio Codium-based IDE, [Positron](https://github.com/posit-dev/positron).

## Installation

1. In VS Code, go to `Code -> Preferences -> User Snippets`
2. Select `r.json` (for R snippets) or `markdown.json` (for R Markdown)
3. Copy and paste the snippets from `snippets.json` in this repository

## Featured Snippets

This collection includes **100+** powerful snippets covering the entire data science workflow:

### Data Import & Manipulation

- Modern tidyverse operations (`|>` pipe operator)
- High-performance data.table operations
- Database connections (MySQL, PostgreSQL, SQLite)
- Spatial data handling with sf

### Visualization

- Complete ggplot2 templates with themes and facets
- Publication-quality plot themes
- Interactive visualization with plotly
- Customizable chart parameters

### Statistical Analysis

- Comprehensive modeling (linear, GLM, mixed effects)
- ANOVA, t-tests, and non-parametric tests
- Modern machine learning workflows with tidymodels
- Cross-validation and model evaluation

### Machine Learning & Advanced Analytics

- Random forest, gradient boosting, and neural networks
- Cross-validation templates with tidymodels
- Time series forecasting with Prophet
- Text mining with tidytext

### Reporting & Reproducibility

- R Markdown report templates
- Shiny application scaffolding
- Parallel processing setup
- Automated EDA templates

## Usage Examples

### Quick Data Pipeline

```r
# Type "tidyverse: pipe chain" for:
data |>
  filter(condition) |>
  mutate(new_var = transformation) |>
  group_by(group_var) |>
  summarize(summary_stats) |>
  arrange(arrangement)
```

### Professional Visualization

```r
# Type "ggplot: scatter with regression" for:
ggplot(data, aes(x = x, y = y)) +
  geom_point(aes(color = group), alpha = 0.7) +
  geom_smooth(method = "lm", se = TRUE) +
  theme_minimal() +
  labs(title = "Scatterplot with Linear Regression", x = "X Label", y = "Y Label")
```

### Machine Learning Workflow

```r
# Type "cross validation" for a complete modeling workflow
```

## Detailed Snippet List

The collection includes snippets for:

- **Data Wrangling**: filter, select, mutate, arrange, join, pivot, etc.
- **Visualization**: All ggplot geoms, themes, facets, and customizations
- **Statistical Tests**: t-tests, ANOVA, chi-square, normality tests
- **Modeling**: Linear models, GLM, mixed effects, machine learning
- **Advanced Analytics**: Time series, text mining, spatial data
- **Functional Programming**: map, walk, reduce, purrr operations
- **Reporting**: R Markdown templates, Shiny app structures
- **Performance**: Parallel processing, data.table operations

See [snippets.json](./snippets.json) for the complete list.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-snippet`)
3. Commit your changes (`git commit -am 'Add some amazing snippet'`)
4. Push to the branch (`git push origin feature/amazing-snippet`)
5. Open a Pull Request

## Requirements

- R 4.0+ (optimized for R 4.3+)
- VS Code with R extension or similar IDE
- Recommended packages: tidyverse, data.table, ggplot2, tidymodels

## License

This project is licensed under the Beerware License - see the [LICENSE](LICENSE) file for details. If you find these snippets useful, consider buying me a beer if we ever meet!

## Acknowledgments

- The R Core Team for their amazing language
- The tidyverse team for revolutionizing data science in R
- The VS Code team for an excellent IDE
- All contributors to this project

---

_Last updated: April 29, 2025_
