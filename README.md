# Network Visualization Presentation

This repository contains a [Quarto](https://quarto.org/) slide deck prepared for the data visualization class at Oregon State University. The presentation introduces network visualization concepts — including graph structure, network metrics, and R-based visualization tools — and uses ongoing dissertation research on disease networks in wheat as a motivating example.

## Dependencies

This project uses [`renv`](https://rstudio.github.io/renv/) to manage R package dependencies.

### Setup

1. Clone the repository:
```bash
   git clone <repo-url>
   cd <repo-folder>
```

2. Open the project in RStudio and install `renv` if you don't have it:
```r
   install.packages("renv")
```

3. Restore the project library:
```r
   renv::restore()
```

4. Render the presentation:
```r
   quarto::quarto_render("network_viz_presentation.qmd")
```

## Key Packages

- `igraph` — graph data structures and algorithms
- `tidygraph` — tidy manipulation of graph objects
- `ggraph` — network visualization via ggplot2
- `patchwork` — combining multiple plots
- `sf` — spatial data handling