# Fuzzing with pattern mining

Conference URL - https://conf.researchr.org/track/issta-2026/issta-2026-research-papers

## Rules

At the time of submission, each paper should have no more than 18 pages for all text and figures, plus unlimited references, using the following templates: Latex or Word (Mac) or Word (Windows). Authors using LaTeX should use the sample-acmsmall-conf.tex file (found in the samples folder of the acmart package) with the acmsmall option. We also strongly encourage the use of the review, screen, and anonymous options as well. In sum, you want to use:

```\documentclass[acmsmall,screen,review,anonymous]{acmart}```

## ToDo
 - How to incorporate doubling the energy in AFL when new path is found? Currently energy yield above 1.0 are ignored which is caused by this doubling in the first place.