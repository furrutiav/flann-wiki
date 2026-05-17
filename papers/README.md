# Contributing a Paper Entry

Add one YAML file per paper in this folder. Use a lowercase, hyphenated filename
based on the paper title, for example:

```text
thinking-like-transformers.yaml
```

Entries should be theory-oriented and relevant to FLaNN: papers that analyze
neural networks through mathematics, computer science, or linguistics, especially
work on expressivity, learnability, interpretability, formal languages,
automata, transformers, RNNs, or state-space models.

Use this schema:

```yaml
title: "Paper Title"
authors:
  - "First Author"
  - "Second Author"
venue: "Conference, journal, workshop, or preprint server"
year: 2024
urls:
  abstract: "https://canonical-paper-page.example"
  pdf: "https://paper-pdf.example"
  arxiv: "https://arxiv.org/abs/xxxx.xxxxx"
abstract: >-
  Prefer the original abstract from the canonical paper page when it is easy to
  find. Keep the text faithful to the source.
summary: >-
  Add a short generated summary explaining why the paper belongs in this
  database.
tags:
  - "transformers"
  - "formal-languages"
  - "expressivity"
```

Before adding a new file, please check that:

- The paper is not already in the folder.
- The source URLs match the paper title.
- The abstract is copied from the original source when available.
- The summary is brief and clearly states the theoretical relevance.
- Tags are lowercase and reusable across papers when possible.
