# Provenance and editorial notes

## Original course sources

The public collection was assembled from the default-branch snapshots of:

- `DSI-EDA-2022/EDA-class-code` — student lesson notebooks, short exploratory assessments, and the midterm prompt. Original repository private at preparation.
- `DSI-EDA-2022/EDA-assignments` — homework prompts and the separately licensed red-wine dataset. Original repository private at preparation.
- [DSI-EDA-2022/EDA-project-ex](https://github.com/DSI-EDA-2022/EDA-project-ex) — public instructor-provided project-organization example, not a student submission.

Exact source revisions, file mappings, hashes, and editorial changes are recorded in [provenance.json](provenance.json). Private originals are not needed to read this public collection. No original Git history was imported; no source repository was modified.

## Authorship

Cassy Dorff is identified as professor or author throughout the source lessons and assignments. The module 10 student text-as-data notebook explicitly credits Colin Henry. The module 11 environmental-mapping lesson was introduced by the GitHub contributor `MyrandaGoesToSpace`; its lack of an author field is not a basis for assigning authorship to Henry. The final-project example was contributed by Cassy Dorff.

This is a selection from a shared course, not a claim that Henry designed every assignment or taught every topic. Existing acknowledgments to other teaching resources remain in the files. This edition's syllabus and navigation were prepared for Henry's teaching portfolio.

## Editorial changes for the public edition

1. Student-facing material is organized into `lessons/`, `assignments/`, `assessments/`, and `project-template/`. Instructor keys and instructor versions, source history, operating-system files, and source repository configuration are excluded.
2. The module 5 data-report prompt replaces the class signup-spreadsheet link and name-entry instructions with a note for public readers. The module 15 survey prompt replaces the live survey-form link with an explanation that survey access is not distributed.
3. The project guide is adapted from the original organizational example. Placeholder binary deliverables and inconsistent historical calendar dates are not carried into the current guide. Its new folder notes describe intended contents, not completed work.
4. The README, reconstructed syllabus, navigation indexes, data notes, and lesson 10 context note are new. The syllabus synthesizes instructional aims; it is not an authentic recovered institutional syllabus.
5. `.md` companions for `.Rmd` sources preserve the lesson prose and code with GitHub-readable code fences. They display the original title, author, and date where present. They are generated text previews, not freshly executed results.

## Historical gaps and cautions

- Folder numbering is preserved. Module 7 contains an instructor key rather than a separate student version and is not published; modules 9 and 14 are absent. The source snapshots do not contain a complete slide collection or original institutional syllabus.
- A module 3 homework title says "Week 4"; the file in `mod4` calls itself "Mod 5"; some notebook dates and the text homework's 2021 date show reuse. These are not silently converted into a definitive 2022 calendar.
- The original project example's presentation-practice date precedes some drafting dates. This edition retains the project sequence without claiming an authoritative historical schedule.
- The module 10 notebook discusses "structural topic" modeling but its stated method is latent Dirichlet allocation. Its historical corpus-specific observations were not recomputed; see the lesson note.
- Some missingness prompts invite classification as MCAR, MAR, or MNAR. Observed patterns can inform discussion but do not by themselves identify an unobserved missingness mechanism. The public edition preserves the historical exercise rather than claiming that the classifications have been established.
- Some data descriptions, package behavior, geographic labels, and external links may be dated. Preservation is not a new substantive validation of those claims.

## Rights

All three source repositories carry the same MIT notice, copyright 2022 DSI-EDA-2022, retained verbatim as [LICENSE](../LICENSE). Course documentation and software are presented under that notice; third-party materials retain their own rights. The one included external dataset is attributed separately in [DATA_AND_REUSE.md](DATA_AND_REUSE.md).

Public access is not an assertion of Vanderbilt endorsement, permission to redistribute every dataset mentioned in a lesson, or permission to publish student work. No student work, grades, or evaluations are included.
