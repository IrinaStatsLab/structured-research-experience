# Zenodo manual upload — simulation-project-template

Go to **https://zenodo.org/uploads/new**

---

## 1. Files

GitHub → repo → **Releases** → **v.1.0.1** (the newer one, with .zenodo.json)
→ right-click **Source code (zip)** → Download. Drag into Zenodo.

---

## 2. Basic information

**Resource type**
```
Software
```

**Title**
```
Simulation Project Template
```

**Publication date** — today (default is fine)

**Creators**
```
Family name:  Gaynanova
Given names:  Irina
ORCID:        0000-0002-4116-0268
Affiliation:  Department of Biostatistics, University of Michigan
```

**Description** (paste as-is)
```
A worked simulation study in R, structured as a starting point for new projects. It compares ridge regression, lasso, and principal component regression under a linear model with correlated covariates.

The template demonstrates modular organization (separate files for data generation, method wrappers, and performance metrics), uniform input/output interfaces across methods, reproducible parallel replication with doRNG, saved raw per-replication output, and separation of computation from visualization.

Companion to "Designing and Reporting Simulation Studies", part of the Structured Research Experience teaching materials.
```

**Version**
```
v1.0.1
```

---

## 3. License

Select: **Creative Commons Attribution 4.0 International (CC-BY-4.0)**

---

## 4. Keywords

```
simulation study
statistics education
reproducible research
project template
R
```

---

## 5. Related works

```
Relation:   is supplemented by
Identifier: https://github.com/IrinaStatsLab/simulation-project-template
Type:       URL
```

Once the teaching-materials DOI exists, also add:
```
Relation:   is part of
Identifier: <concept DOI of structured-research-experience>
Type:       DOI
```

---

## 6. Publish

Record the **concept DOI** from the "Cite all versions?" line.
