# Text as data: Colin Henry's live-coding lesson

**Original author:** Colin Henry. **Original notebook date:** October 27, 2022.

- [Read the student lesson](day2-live-coding-student.md)
- [Download the editable R Markdown source](day2-live-coding-student.Rmd)

The lesson moves from document inspection and tokenization to stop-word choices, word counts, TF-IDF, dictionary-based sentiment, and latent Dirichlet allocation (LDA). Its final task asks students to compare model-derived topics with existing poem tags and interpret the correspondence. This offers a concrete example of teaching computational methods through analytical decisions rather than treating software output as self-explanatory.

The original Poetry Foundation corpus is **not redistributed**. The notebook expects a local `subset-poetry-data.rds` file. Retained references to particular documents, weights, and topics describe the historical demonstration; no results have been regenerated for this portfolio. The instructor version is not included.

## Terminology for reuse

The topic model described in this lesson is LDA, not a structural topic model with document covariates. A topic's beta values represent probabilities of terms conditional on that topic; gamma values describe topic proportions for a document, not validated class-membership probabilities. Comparing these topics with existing tags is an exploratory interpretation task, not independent predictive validation. These notes clarify reuse without silently rewriting the historical student notebook.
