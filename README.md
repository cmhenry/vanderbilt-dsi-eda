# Exploratory Data Analysis in R

**Vanderbilt University · Data Science Institute · 2022**

A public teaching collection showing how exploratory data analysis connects a substantive question to data inspection, visualization, and clear written interpretation. These materials were consolidated from the course's three original repositories for Colin M. Henry's teaching portfolio.

**Course instructor:** Cassy Dorff. **Featured contribution:** Colin Henry's text-as-data live-coding lesson. Original author credits and the course's MIT license are retained; this collection does not imply sole authorship of the course.

## Start here

- **[Syllabus](SYLLABUS.md)** — a readable reconstruction of the course's aims, sequence, and assessment approach. Also available as a **[downloadable PDF](SYLLABUS.pdf)**.
- **[Text-as-data lesson](lessons/mod10/day2-live-coding-student.md)** — Henry's guided introduction to tokenization, stop words, TF-IDF, sentiment dictionaries, and topic models. [Teaching and data notes](lessons/mod10/README.md).
- **[Data report assignment](assignments/mod5/mod5_hw.md)** — an open-ended task asking students to investigate data provenance, pose a question, select two graphics, and explain their analytical decisions.
- **[Missing-data lesson](lessons/mod6/mod6_missing_data_student.md)** — scaffolded investigation using R's built-in `airquality` data.
- **[Final-project guide](project-template/README.md)** — an organized path from raw data and preprocessing to reproducible findings, a report, and a presentation.

## What the materials show

The course serves first-year master's students in data science. Exercises move from inspecting the unit of analysis and variable types to selecting graphics, explaining missingness, and exploring text, spatial, temporal, and clustered data. Students are repeatedly asked to interpret results in complete sentences and justify their choices rather than submit code alone.

Student notebooks combine worked demonstrations, discussion questions, and deliberately unfinished code. The assignment sequence gradually gives students more responsibility for choosing data and questions. The final project connects exploratory work to an organized analytical repository and audience-ready deliverables.

## Browse the collection

- **[Lessons](lessons/README.md):** data summaries; bivariate graphics; distributions and correlation; flow diagrams; missing data; text analysis; environmental and spatial mapping; clustering.
- **[Assignments](assignments/README.md):** R Markdown, exploratory graphics, data reports, missingness, text analysis, time series, clustering, and a final messy-data exercise.
- **[Assessments](assessments/README.md):** two short exploratory challenges and the student midterm prompt, without solutions.
- **[Project template](project-template/README.md):** folder structure and project communication guidance.

Readable `.md` companions let visitors inspect every R Markdown teaching document directly on GitHub. The `.Rmd` files remain editable sources. Companions reproduce source text and code; they are **not executed notebooks** and contain no newly generated results.

## Using the R materials

No software or account is needed to browse. To work through a notebook, use R and an editor such as RStudio, install its listed packages, and run code from that notebook's directory. R Markdown rendering additionally requires `rmarkdown`, `knitr`, and Pandoc; PDF rendering also requires a LaTeX installation. Student exercises must be completed before a full document can necessarily knit.

Begin with package-provided data in the missing-data lesson, the [flow-diagram lesson](lessons/mod5/mod5_lecture_students.md), or the [clustering lesson](lessons/mod13/mod13_student.md). These do not require the withheld local course datasets, although the R packages must be installed. The red-wine dataset is included with separate attribution. See **[Data, dependencies, and reuse](docs/DATA_AND_REUSE.md)** before running other examples.

## About this public edition

This is a curated teaching archive, not a current course offering or a complete executable distribution of the 2022 course. It excludes student survey responses, instructor keys, unverified data copies, and private Git history. Links to class signup sheets and the class survey form have been removed. Historical dates and submission instructions in retained handouts describe the original classroom context, not current deadlines.

## Credit and reuse

Course materials: Cassy Dorff and Colin Henry.

The original **[MIT license](LICENSE)** applies to the course code and documentation as provided by the source repositories. Third-party datasets and quoted material retain their own terms; see [data attribution](docs/DATA_AND_REUSE.md). The new syllabus, navigation, and editorial documentation are provided under MIT as well. This is a personal teaching portfolio, not an official Vanderbilt publication.
