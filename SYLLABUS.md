# Exploratory Data Analysis in R

**Vanderbilt University · Data Science Institute · 2022 teaching collection**

**Instructor:** Cassy Dorff. **Featured teaching contribution and public edition:** Colin M. Henry.

**Document status:** Reconstructed syllabus for a teaching portfolio. This document summarizes the surviving course notebooks, assignments, assessments, and project guidance. It is not the original 2022 institutional syllabus. Learning objectives are synthesized from the activities; module numbers follow the archive rather than a newly invented weekly calendar.

## Course description

Exploratory data analysis is the process of learning what a dataset contains, asking productive questions about it, and communicating defensible interpretations. This course introduces that process in R through data summaries, visualizations, missing-data investigations, and applications to text, geographic, temporal, and multivariate data.

The emphasis is on judgment as well as technique: What is the unit of analysis? How were the data produced? Which comparison does a graphic support? What information is missing? How might an apparently clear pattern be misleading? Students combine code with written explanations and develop an organized final analytical project.

## Audience and preparation

The course is intended for first-year master's students in data science. The surviving lessons build on elementary R operations, including objects, indexing, data frames, and package loading. Early assignments introduce R Markdown and GitHub-based submission. The archive does not establish a formal prerequisite course, credit-hour value, or complete meeting schedule.

## Reconstructed learning objectives

By working through the course activities, students practice how to:

1. Inspect and describe a dataset's provenance, unit of analysis, dimensions, variable types, and organization.
2. Wrangle and summarize data, including subsetting, grouped summaries, and the construction of interpretable measures.
3. Select, label, and interpret graphics for distributions, relationships, flows, and patterns across time and space.
4. Investigate the amount and pattern of missing data and explain the assumptions and limits of possible missingness mechanisms.
5. Explore text and multivariate data using tokenization, term weighting, sentiment dictionaries, topic models, and k-means clustering.
6. Communicate an exploratory question, analytical decisions, findings, and limitations through reproducible code, a written report, and a presentation.

## Learning format

Student-facing R Markdown notebooks combine explanation, demonstration, discussion, and incomplete code to be developed during class. Homework revisits the techniques with a different dataset or a more independent question. Short exploratory challenges and the midterm ask students to make and defend analytical choices with less scaffolding.

Written interpretation is integral to the work. Students explain what a graphic shows, why they selected it, how it might mislead, and what they learned from the process. They are not asked simply to reproduce a plot or report a statistic.

## Course sequence represented in the archive

- **Module 1 — Reproducible reporting.** Use R Markdown, knit a document, and submit source and readable output through GitHub.
- **Module 2 — Looking at data.** Inspect structure and variable names, use indexing and summaries, distinguish long and wide layouts, and compare grouped quantities. The homework uses `UCBAdmissions`.
- **Module 3 — Bivariate visualization.** Develop scatterplots and meaningful measures using school-level data. The homework asks students to compare storm harms and costs and consider misleading interpretations.
- **Module 4 — Distributions and correlation.** Use histograms, density plots, boxplots, and scatterplots. Consider missing observations, counts versus proportions, and how to communicate relationships.
- **Module 5 — Flows and independent exploration.** Explore flight flows with alluvial diagrams. Complete a data report organized around provenance, a motivating question, two final graphics, and reflection on data preparation.
- **Module 6 — Missing and messy data.** Count and visualize missingness, examine patterns across variables, and discuss implications. The homework introduces MCAR, MAR, and MNAR through a workout-study scenario.
- **Module 8 — Midterm.** Describe unfamiliar data, assess missingness, summarize distributions, and pose and answer exploratory questions with justified graphics.
- **Module 10 — Text as data.** Tokenize documents; examine stop words, word counts, TF-IDF, sentiment dictionaries, and latent Dirichlet allocation. Henry's live-coding notebook connects these steps to interpretation and domain knowledge.
- **Module 11 — Environmental mapping.** Explore NetCDF structure and NOAA sea-surface-temperature data; use spatial coordinates and raster representations to compare patterns.
- **Module 12 — Spatial and temporal data.** Join geographic and substantive data to construct maps. The homework covers time-series objects, line plots, comparison across countries, autocorrelation, and decomposition.
- **Module 13 — Clustering.** Examine scaling and distance; run and interpret k-means; compare choices of cluster count and graphical presentation.
- **Module 15 — Synthesis.** Combine a presentation-quality graphic with an attempted second analysis using clustering, text sentiment, or mapping. A final homework returns to the class survey to practice cleaning and interpretation; responses are not distributed publicly.

Module 7 has instructor-only missing-data material that is not released here. Modules 9 and 14 are absent from the source snapshots. The preserved numbering is not evidence that each module occupied exactly one week. Some handout titles and dates reflect reuse and do not align perfectly with folder numbers.

## Assessment and deliverables

- **Homework and data reports:** R Markdown or R code, readable output where requested, substantive interpretation, and visible analytical work. The data-report assignment requires two selected final plots with explanations, not an uncurated collection of graphics.
- **Short exploratory challenges:** independent analysis of unfamiliar data, presentation-quality graphics, and concise interpretation. The later challenge combines a main graphic with an attempted second analytical technique.
- **Midterm:** an open-notes individual assessment, with sections on data description, missingness, distributions, exploratory graphics, and justified interpretation. The historical prompt allocates 20, 20, 40, and 20 points to its four parts.
- **Final project:** a focused analytical question, organized preprocessing and data files, code that reproduces the main findings, a written report, and presentation slides. The original guidance emphasizes clear repository documentation and high-quality graphics and tables rather than screenshots.

The surviving files provide some assignment-specific point values, but not an authoritative overall grade formula. No percentage weights, late-work rules, or complete examination calendar are reconstructed here.

## Tools, readings, and public access

R, R Markdown, Git, and GitHub support the original workflow. Package use varies by lesson: the tidyverse and ggplot2 support most exploration; specialized lessons use missing-data, text-analysis, spatial, or clustering packages. Introductory reading includes the historical R Markdown chapter of *R for Data Science*, with additional references in the individual notebooks.

The public repository provides text-readable Markdown companions and editable R Markdown files. Student code blanks are intentional. Some exercises use data supplied by R packages; others require external data or files withheld from this public edition. The class survey and private coordination links are not public resources. The historical Google Maps extension requires a separate API account and key; it is not needed to browse the materials or study the package-data mapping examples.

See the repository's data and reuse guide before running exercises. This edition has not rerun the R lessons or verified historical service endpoints. No student submissions, grades, evaluations, or claims of measured learning gains are included. Current institutional accessibility, integrity, and accommodation policies must be supplied by an instructor adapting the materials for a new offering.
