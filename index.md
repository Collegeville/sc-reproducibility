# Reproducibility for the Supercomputing Conference Series

### Quick Links to LaTeX source ZIP files

- Description Appendix: [sc-description-appendix-20180127.zip](https://collegeville.github.io/sc-reproducibility/sc-description-appendix-20180127.zip)
- Trust Appendix: [sc-trust-appendix-20180127.zip](https://collegeville.github.io/sc-reproducibility/sc-trust-appendix-20180127.zip)


## Background
SC16 introduced the first reproducibility efforts for the SC conference series technical papers program. This initial effort followed the strategy of Result and Artifact Review and Badging, and asked for volunteers to submit an _artifact description (AD)_ appendix with their paper that described the details of their software environment and computational experiments to the extent that an independent person could replicate their results.

About 30 authors volunteered for this effort, 9 submitted appendices, and from among those, 3 papers were chosen as finalists and one will be used in the Student Cluster Competition for 2017. All papers that completed the appendix had it combined with their final paper in a single document, and had the ACM “Artifacts Available” badge added to their article, available in the ACM Digital library.

SC17 continued the AD practice, adding the requirement that such an appendix is necessary for a paper to be considered for best paper or best student paper.  SC17 also introduced the _computational results analysis_ (CRA) appendix, which enables authors to describe approaches used to better ensure the trustworthiness of their computational results.  40% of submitted papers had an AD appendix, and slightly more that half of accepted paper had the AD appendix.  Nine submitted papers had a CRA appendix, six of which were accepted.

## Reproducibility at SC18

SC18 will include reproducibility efforts in three technical program elements:
1. **Technical Papers:** The SC18 process will be identical to SC17, except trust (aka, computational results analysis) appendices will not have a page limit.
2. **Workshops:** Workshop organizers will have the option to request description appendices from their authors.
3. **Posters:** Poster submissions will optionally include a description appendix.  The description appendix is required to be considered for best paper or best student paper.

### (Artifact) Description Appendix

We will require this appendix in order for a paper to be considered for the Best Paper and Best Student Paper awards. Authors will provide the completed appendix (at most 2 pages), along with their submission.
Notes:

- A paper cannot be disqualified based on information provided or not provided in this appendix, nor if the appendix is not available.
- The availability and quality of an appendix can be used in ranking a paper. In particular, if two papers are of similar quality, the existence and quality of the appendices can be part of the evaluation process.
- In order to be considered for Best Paper or Best Student Paper, the authors must submit an Artifact Description appendix.

### Trust Appendix (formerly known as the Computational Results Analysis Appendix)
Each year, SC has a significant number of papers that report results from boutique environments such as leadership computing platforms, prototype hardware for next generation systems, or other environments where reviewers would be unable to replicate the results, and even the authors themselves may be challenged to do so. In this setting, authors can improve trustworthiness of results by other means. The Trust Appendix provides authors with an opportunity to discuss how trustworthiness of their results can be increased even when the computational experiments cannot be rerun. Approaches include verification and validation efforts prior to, during and after execution of computational experiments such that metadata about code and results can be used in post-execution analysis to confirm that the experiment executed as expected, with some extra assurance that the results are correct.

#### Trust Appendix Details
- The Trust Appendix initiative is intended to spur community exploration of upstream diagnostics and peri-execution time V&V that will give the authors, reviewers and the community at large greater confidence that published non-replicable results are correct.
  - Authors can volunteer to produce an appendix describing their approach and results.
  - We will select a few of these papers and use them in the student cluster competition for students to study and exercise as a part of the competition.
- Some types of additional diagnostics could be:
  - Validation of the timers (time something with a known execution time, determine the precision and statistical variability of the timer).
  - Confirm results for a manufactured solution.
  - Test the analytics of the problem, e.g., generate a problem with known spectral properties and test its behavior.

### Engaging the Student Cluster Competition
We will engage students once again this year in the SC reproducibility initiative. We will continue the use of the Artifact Description Appendices in the Student Cluster Competition, similar as we did for SC16 and SC17. We also plan to include an effort related to the Trust Appendix.

### Resources

- [SC18 Reproducibility Initiative Author FAQ](https://collegeville.github.io/sc-reproducibility/AuthorFAQ.html)
- [SC18 Reproducibility Initiative Reviewer FAQ](https://collegeville.github.io/sc-reproducibility/ReviewerFAQ.html)
- [Artifact Description Appendix Template](https://collegeville.github.io/sc-reproducibility/DescriptionAppendixTemplate.html)
- [Trust Appendix Template](https://collegeville.github.io/sc-reproducibility/TrustAppendixTemplate.html)

For more information contact: Michael Heroux <maherou@sandia.gov>
