# Reproducibility for the SC Conference Series

## Background
The SC Conference Series introduced  the reproducibility initiative in the 2016 Technical Papers program, with a strategy of Result and Artifact Review and Badging. Authors were asked to voluntarily submit an _artifact description (AD)_ appendix along with their paper, describing the details of their software environments and computational experiments to the extent that an independent person could replicate their results.

About 30 authors volunteered for this effort. Nine submitted AD appendices, three among them were chosen as finalists, and one was used in the SC17 Student Cluster Competition. All papers that included an AD appendix were given an ACM Artifacts Available badge, and the papers with their appendices are archived in the ACM Digital Library.

The reproducibility initiative was continued at SC17, with the added requirement that an AD appendix be included in order for a paper to be considered for Best Paper or Best Student Paper. SC17 also introduced the _computational results analysis (CRA)_ appendix, which enables authors to describe approaches used to better ensure the trustworthiness of their computational results. 40% of submitted papers and more than 50% of accepted papers included an AD appendix. Nine submitted papers included a CRA appendix, six of which were accepted.

SC18 will continue these efforts, extending the option of submitting an AD appendix to the Workshops and Posters programs. Inclusion of an AD appendix will remain optional for Papers, and will remain a requirement for Best Paper and Best Student Paper selections. The CRA appendix has been renamed the _artifact evaluation (AE)_ appendix and will continue to be optional.

## Why Focus on Reproducibility for SC?

Reproducibility is at the heart of the scientific method. The SC Conference Series is committed to introducing elements that highlight, enhance, and reward participant efforts to improve reproducibility. Since we started the SC reproducibility initiative, we have observed the following:
- **Producing an AD appendix improves both effectiveness and efficiency:** 
  - The AD appendix provides information (details of the computing platform, software environment,etc.) that should be in any paper with computational results.  
  - If a paper has no computational results, the appendix only needs to mention that computational results are not part of the paper.  
  - The AD appendix provides uniform and thorough descriptions of this basic information, making it easier for authors to provide the content, and reviewers and readers to understand it.
  - The SC review process for appendices can support double-blind requirements that are similar to handling self citations.
- **Provision of an AE appendix is an important approach especially suited to SC authors:**
  - A significant number of SC contributions are executed in "boutique" environments, where reviewers, readers, and even the authors themselves may have difficulty re-running the computational experiment.
  - The AE appendix enables authors to describe how they verify and validate their computational results, providing increased evidence that their results are trustworthy, and providing best practices descriptions to the community that can be adopted by others who want to improve their own efforts.
 
## Reproducibility at SC18

The reproducibility initiative will be active in three programs at SC18:
1. **Papers:** The SC18 process will be identical to SC17, except that the artifact evaluation appendices will be limited to four pages. An artifact description appendix (up to two pages) will be required for consideration for Best Paper and Best Student Paper.
2. **Workshops:** Workshop organizers will have the option to request artifact description appendices from their authors.
3. **Posters:** Poster submissions will have the option to include an artifact description appendix. An AD appendix will be required for consideration for Best Poster or Best Student Poster.

### Artifact Description Appendix

- A submission cannot be disqualified based on information provided or not provided in this appendix, nor if no appendix is provided.
- The inclusion and quality of an appendix may be considered in evaluating a submission, particularly in ranking two submissions of similar quality.
- In order to be considered for Best Paper or Best Student Paper, the authors must submit an Artifact Description appendix.

### Artifact Evaluation Appendix
Each year, SC receives a significant number of submissions reporting results from boutique environments such as leadership computing platforms, prototype hardware for next generation systems, or other environments where reviewers would be unable to replicate the results – and even the authors themselves may be challenged to do so. The AE appendix gives authors the opportunity to discuss how the trustworthiness of their results can be increased even when the computational experiments cannot be rerun. Approaches include verification and validation efforts prior to, during, and after execution of computational experiments such that metadata about code and results can be used in post-execution analysis to confirm that the experiment executed as expected, with some extra assurance that the results are correct.

#### Artifact Evaluation Appendix Details
- The AE Appendix initiative is intended to spur community exploration of upstream diagnostics and peri-execution time verification and validation that will give the authors, reviewers, and the community at large greater confidence that published non-replicable results are correct.
  - Authors can volunteer to produce an appendix describing their approach and results.
  - We hope to use a selection of these submissions in the Student Cluster Competition for students to study and exercise as a part of the competition.
- Some types of additional diagnostics could be:
  - Validation of the timers (time something with a known execution time, determine the precision and statistical variability of the timer).
  - Confirmaation of results for a manufactured solution.
  - Testing the analytics of the problem, (e.g., generate a problem with known spectral properties and test its behavior).

### Engaging the Student Cluster Competition
We will engage students in the SC reproducibility initiative again this year by continuing to use these appendices in the Student Cluster Competition.

### Resources

- [SC18 Reproducibility Initiative Author FAQ](https://collegeville.github.io/sc-reproducibility/AuthorFAQ.html)
- [SC18 Reproducibility Initiative Reviewer FAQ](https://collegeville.github.io/sc-reproducibility/ReviewerFAQ.html)
- [Artifact Description Appendix Template](https://collegeville.github.io/sc-reproducibility/ArtifactDescriptionAppendixTemplate.html)
- [Artifact Evaluation Appendix Template](https://collegeville.github.io/sc-reproducibility/ArtifactEvaluationAppendixTemplate.html)

## Chair

### SC18 Reproducibility Chair

Michael A. Heroux, Sandia National Laboratories, St. John’s University

## Contact

Questions about SC’s reproducibility initiative?

Contact us: Michael Heroux <maherou@sandia.gov>
