# Zenodo manual upload — copy-paste sheet

Go to **https://zenodo.org/uploads/new**

---

## 1. Files

On GitHub: repo → **Releases** → **v1.0.0** → right-click **Source code (zip)** → Download.
Drag that zip into the Zenodo upload box.

---

## 2. Basic information

**Resource type**
```
Lesson
```

**Title**
```
Structured Research Experience: Teaching Materials for Scientific Communication, Simulation Studies, and Reproducibility
```

**Publication date** — today's date (default is fine)

**Creators** — click *Add creator*
```
Family name:  Gaynanova
Given names:  Irina
ORCID:        0000-0002-4116-0268
Affiliation:  Department of Biostatistics, University of Michigan
```

**Description** (paste as-is)
```
Open teaching materials for running a structured research experience in statistics, covering scientific communication (oral and written), the design and reporting of simulation studies, and reproducible research practice.

Contents:

- Oral Presentation Assessment Rubric - five criteria scored 0-3, with separate content tracks for statistical/data analysis and general scientific presentations.
- Academic Writing - the writing process, paper structure for statistics and domain journals, what an introduction must accomplish, why papers get rejected, and a feedback checklist.
- Designing and Reporting Simulation Studies - organized around four components (Goal, Design, Implementation, Summary), covering data-generating mechanisms, uniform wrapper interfaces, Monte Carlo standard error, seeds and parallel RNG, and reporting.
- Reproducible Project Workflows - Git and GitHub from installation onward, R projects, and project structure.

Each document is written in Quarto and rendered to PDF via the Typst engine. Sources are included so the materials can be adapted.
```

**Version**
```
v1.0.0
```

---

## 3. License

Select: **Creative Commons Attribution 4.0 International (CC-BY-4.0)**

---

## 4. Keywords

Add each separately:
```
statistics education
open educational resources
scientific communication
simulation studies
reproducible research
undergraduate research
assessment rubric
Quarto
R
```

---

## 5. Related works  (optional but worth doing)

```
Relation:   is supplemented by
Identifier: https://github.com/IrinaStatsLab/structured-research-experience
Type:       URL
```

---

## 6. Publish

Click **Publish**. The DOI appears immediately on the record page.

Look for: **"Cite all versions? You can cite all versions by using the DOI 10.5281/zenodo.XXXXXXX"**
That is the **concept DOI** — the one for NSF reports.

---

## Note

Doing this manually does not prevent the GitHub integration from working later.
If it eventually fires, you get a second record; you can delete it or link the two.
