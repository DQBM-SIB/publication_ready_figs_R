# Publication-Ready Figure Generation in R

This repository contains the materials for the course "Publication-Ready Figure Generation in R".

## Learning Objectives

- **Analyze the principles of effective data visualization:**
  - **Explain** the importance of clarity, accuracy, and aesthetics in creating publication-ready figures.
  - **Identify** common pitfalls in data visualization and how to avoid them.
- **Apply base R graphics for figure creation:**
  - **Create** basic plots (e.g., scatterplots, bar charts, histograms) using base R functions like `plot()`, `barplot()`, and `hist()`.
  - **Customize** plots with titles, labels, legends, and color schemes.
- **Construct advanced visualizations using ggplot2:**
  - **Build** complex and layered visualizations using the `ggplot2` package.
  - **Apply** themes, scales, and `geoms` to create polished and publication-ready figures.
- **Adapt figures for specific publication requirements:**
  - **Adjust** figure dimensions, resolutions, and formats (e.g., PDF, PNG, TIFF) for journal submissions.
  - **Modify** fonts, line weights, and other stylistic elements to meet publication guidelines.
- **Integrate statistical annotations and summaries:**
  - **Add** statistical summaries (e.g., regression lines, confidence intervals) to figures.
  - **Annotate** plots with p-values, correlation coefficients, or other relevant statistics.
- **Generate high-quality figures:**
  - **Use** functions like `ggsave()` or `pdf()` to export figures in high resolution.
  - **Ensure** exported figures meet the technical requirements of target journals or platforms.
- **Assemble multi-panel figures:**
  - **Combine** multiple plots into a single figure using tools like `patchwork`.
  - **Align** and **arrange** subplots to effectively communicate complex data.
- **Implement best practices for reproducibility:**
  - **Write** clean and reusable R scripts for figure generation.
  - **Document** code and workflows to ensure reproducibility and transparency.

## Project Structure

This project is structured as follows:

- `_quarto.yml`: Configuration file for Quarto.
- `index.qmd`: The main page of the course website, containing the learning objectives.
- `qmd/`: Directory containing Quarto markdown files for course content.
- `styles.css`: Custom CSS for styling the website.
- `docs/`: Directory where the rendered website is built.

## Prerequisites

- **Basic R Programming Skills:**
  - Understanding R syntax (objects, functions, operators).
  - Ability to create and manipulate basic data structures: vectors, factors, data frames, and lists.
  - Familiarity with indexing and subsetting data.
  - Writing simple scripts in RStudio or another R IDE.
  - Reading and importing data (`read.csv()`, `read.table()`, or `readr`).

You can evaluate your skills here:
- [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSdIyeuabd_ZOWXgI1MWHapmaOMu20L9ESkLDZiWnpmkpujyOg/viewform)
- [Coursera R Programming Skill Assessment](https://www.coursera.org/resources/r-programming-skill-assessment)
- [NCEAS R Review and Assessment](https://nceas.github.io/oss-lessons/r-review-and-assessment/r-review-and-assessment.html)

## Computational Requirements

- R 4.5.1
- RStudio (latest version)
- `renv` R package installed: [renv documentation](httpss://rstudio.github.io/renv/articles/renv.html)

## Build Instructions

To build this course website locally, follow these steps:

1.  **Install Quarto:** If you don't have Quarto installed, follow the instructions on the [Quarto website](https://quarto.org/docs/get-started/).
2.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/publication_ready_figs_R.git
    cd publication_ready_figs_R
    ```
3.  **Render the website:** Open the project in RStudio and run the following command in the R console, or execute it in your terminal within the project directory:
    ```bash
    quarto render
    ```
    This will generate the `docs/` directory containing the static website.
4.  **Preview the website:** Open `docs/index.html` in your web browser to view the local build.



## Contributing

Contributions are welcome! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.