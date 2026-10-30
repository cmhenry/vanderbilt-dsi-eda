# Data, dependencies, and reuse

This collection is designed first for inspection of teaching practice. It does not publish the original class's full data holdings or promise that every historical exercise will run unchanged.

## Included dataset

`assignments/mod4/winequality-red.csv` is the red-wine portion of **Wine Quality**, by Paulo Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis (2009), UCI Machine Learning Repository. DOI: [10.24432/C56S3T](https://doi.org/10.24432/C56S3T).

The [official UCI record](https://archive.ics.uci.edu/dataset/186/wine+quality) states **[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)**. The course copy is retained without alteration; this dataset is not relicensed under the repository's MIT license. The file uses semicolon-separated fields.

## Data available through R packages

Several lessons use data supplied by an installed R package rather than by this repository:

- `airquality`, `UCBAdmissions`, `USArrests`, `EuStockMarkets`, and `mtcars`: R's standard datasets. Useful entry points include the missing-data lesson, the module 2 homework, and the clustering lesson.
- `nycflights13::flights`, `hflights::hflights`, and `gapminder::gapminder`: install the corresponding package and consult its documentation and data terms.
- Mapping examples use map data from R packages. Some later examples additionally contact online map providers.

These package datasets are referenced, not copied into this repository. Each package and dataset retains its own license and attribution.

## Files deliberately not redistributed

- **Class survey responses:** omitted wherever they occurred. The survey-form URL and the dataset signup spreadsheet URL are removed from the public prompts; no student responses or signup records are included.
- **Poetry and other text corpora:** Poetry Foundation data, tweets, email bodies, television dialogue, news headlines, and quiz-show text are not bundled. Public availability or prior classroom use does not establish redistribution permission.
- **Other local course datasets:** brewery, school, election, health, workout, COVID, and midterm data copies are not bundled where provenance, consent, or redistribution terms were not established for this edition. The original Nashville school-data identifier returned 404 during preparation.
- **Project-example binaries:** placeholder spreadsheets and a sample PDF are replaced by text guidance rather than presented as student work or substantive results.

No substitute dataset or synthetic student record has been inserted. References to withheld filenames remain in historical notebooks so their teaching context is visible.

## Dependencies and cautions by activity

- **Modules 2–4:** flight and air-quality sections use package data; brewery, school, and election sections require their original local data. Only the wine portion of the module 4 homework has an included external dataset.
- **Module 5:** the alluvial lesson uses `hflights`; the quickfire's state-health data are withheld. The data-report task has a public-edition note in place of the old signup-sheet instructions.
- **Module 6:** the lesson uses `airquality`; the workout homework's local CSV is withheld.
- **Midterm and module 15:** prompts are retained as assessment evidence; their local data are withheld.
- **Module 10:** the poetry student notebook expects `subset-poetry-data.rds` with document identifiers and text. It is a teaching artifact, not runnable as distributed. The text homework likewise requires a separately obtained, appropriately licensed corpus. See [text-lesson notes](../lessons/mod10/README.md).
- **Module 11:** the NOAA lesson retrieves remote NetCDF data and can require substantial memory and network transfer. It was not executed during preparation. The optional coral-location CSV is not bundled.
- **Module 12:** package-data map examples are separate from the historical Google Maps extension. The extension can install packages and use billable APIs; do not run an entire file without reviewing it. Time-series homework uses package data.
- **Module 13:** the class notebook uses `USArrests`; the homework's COVID CSV is withheld.

R and its package environment were not available on the preparation host, so no R-runtime or rendering verification is claimed. Historical instructions may rely on older package behavior, disabled services, downloads, or credentials. Student files deliberately contain code blanks and are not expected to knit before learners complete them.
