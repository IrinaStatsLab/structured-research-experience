# Project Outcomes Report — DRAFT v2

**Award:** DMS-2422478 (formerly DMS-2044823, Texas A&M University)
**Title:** CAREER: Next-Generation Methods for Statistical Integration of High-Dimensional Disparate Data Sources
**PI:** Irina Gaynanova · **Period:** 06/01/2021 – 05/31/2026

---

Modern scientific studies increasingly collect many different kinds of measurements on the same set of subjects. A single biomedical study may gather genomic sequences, microbial abundances, brain images, and continuous streams of data from wearable sensors, each capturing a different facet of the same individuals. Methods for analyzing each data type on its own are well established. Combining them is much harder: the measurements differ in scale and in statistical behavior, and the signal of scientific interest is often shared across several sources while other structure is specific to just one. Separating what the sources hold in common from what each contributes individually is the central problem this project addressed.

A further difficulty is that many modern measurements do not behave like the well-conditioned continuous variables classical methods assume. Microbiome and single-cell sequencing data contain large numbers of exact zeros; other measurements are binary, skewed, or take the form of whole distributions rather than single numbers. This project developed statistical methods that accommodate these features directly, together with the theoretical guarantees and open-source software needed for others to use them.

## Intellectual Merit

The project produced new methodology along three connected lines. First, it developed dimension reduction, classification, and graphical modeling frameworks for mixed and zero-inflated data within a unified semi-parametric framework, establishing that these methods attain the same statistical accuracy as classical counterparts while making substantially weaker assumptions. Second, it developed methods for data arriving as functions or distributions rather than single values, including a distributional regression algorithm more than a thousand times faster than previous implementations, making subsampling-based inference and biobank-scale analyses feasible. Third, it introduced a formulation of partially shared structure across data sources based on hierarchical low-rank constraints, and subsequently derived explicit rates of convergence for estimating shared and source-specific structure, closing a gap that earlier work had left open.

Methods were developed alongside scientific collaborations that tested them on real problems: identifying associations between pre-chemotherapy gut microbiome profiles and treatment outcomes in pediatric leukemia patients; analyzing cortical surface imaging data in autism; and quantifying the effect of sleep apnea on nighttime glucose control by jointly analyzing two classes of wearable device.

The award produced twenty peer-reviewed publications in statistics, machine learning, and domain science venues, including Biometrika, the Journal of the American Statistical Association, Biometrics, the Annals of Applied Statistics, the Journal of Machine Learning Research, and Bayesian Analysis. One publication received the Journal of the American Statistical Association reproducibility award, recognizing excellence in reproducible analysis, open data and software, and end-to-end workflows. All methods were released as open-source R packages, covering continuous glucose monitoring data, blood pressure data, wearable heart rate data, distributional regression, and non-Gaussian component analysis for data integration.

## Broader Impacts

The project's educational aim was to improve how students are prepared to conduct research, and the need proved greater than anticipated. Undergraduates arriving in research settings are typically well trained in coursework but not in what research actually demands: version control, reproducible workflows, code that runs on someone else's machine, designing a simulation study capable of answering a question, and communicating results in writing and in talks.

The PI developed a structured research experience program treating these as teachable skills rather than things absorbed by osmosis. It became a new upper-level undergraduate course, was adopted by another instructor at the same institution, and its communication components were later adapted for a master's-level biostatistics capstone. Research from the award also reshaped a graduate course in multivariate analysis, and supported a new short course on digital health technologies first offered at the 2026 Joint Statistical Meetings.

More than twenty-five undergraduate students participated in research through this program and associated software projects, with deliberate recruitment of students from groups underrepresented in statistics. Their work led to co-authorship on peer-reviewed publications and software, poster and presentation awards at regional and university symposia, an honors thesis completed with distinction, and admission to doctoral programs. The award also supported one postdoctoral researcher and several doctoral students, two of whom completed dissertations drawing on this work.

Instructional materials from the program — covering oral and written scientific communication, the design and reporting of simulation studies, and reproducible research workflows — along with template repositories for organizing reproducible computational projects, have been publicly released under an open license so that other instructors and research groups can adopt and adapt them.
