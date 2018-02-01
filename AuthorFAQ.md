# SC Reproducibility Author FAQ

SC17 continued efforts started at SC16 to promote reproducibility of scientific results in the SC Technical Papers program. SC16 introduced an _Artifact Description _appendix, an optional appendix for SC16 submissions. SC17 continued with this optional appendix and introduce a second, complementary, and also optional, _Computational Results Analysis_ appendix. SC18 will continue the SC17 efforts, and extend the use of the Artifact Description appendix to the Workshops and Posters events.

This FAQ addresses questions that authors and reviewers might have about these appendices.

**Q. Are the Artifact Description and Artifact Evaluation appendices required in order to submit a paper to SC18?**

A. No. These appendices are  **not** required. If you do not submit any appendix, it will not disqualify your submission. At the same time, if two papers are otherwise comparable in quality, the existence and quality of appendices can be a factor in ranking one paper over another. Also, in order for your paper to be considered for Best Paper or for Best Student Paper awards, you must submit an Artifact Description appendix.

**Q. Is the Artifact Description appendix required in order to be considered for Best Paper or for Best Student Paper SC18?**

A. Yes. If you want your paper to be considered for Best Paper or for Best Student Paper awards, it must be included in the Artifact Description appendix.

**Q. Is the Artifact Evaluation appendix required in order to be considered for the Best Paper or Best Student Paper SC18?**

A. No. The Artifact Evaluation appendix is completely optional.

**Q. Do I need to make my software open source in order to complete the Artifact Description appendix? **

A. No. It is not required that you make any changes to your computing environment in order to complete the appendix. The Artifacts Description appendix is meant to provide information about the computing environment you used to produce your results, reducing barriers for future replication of your results. However, in order to be eligible for the ACM Artifacts Available badge (see below), your software must be downloadable by anyone without restriction.

**Q. Who will review my appendices?**

A. The Artifact Description and Evaluation appendices will be submitted at the same time as your paper and will be reviewed as part of the standard review process by the same reviewers who handle the rest of your paper.

**Q. Does the Artifacts Description appendix really impact scientific reproducibility?**

A. The Artifact Description appendix is simply a description of the computing environment used to produce the results in a paper. By itself, this appendix does not directly improve scientific reproducibility. However, if this artifact is done well, it can be used by scientists (including the authors at a later date) to more easily replicate and build upon the results in the paper. Therefore, the Artifacts Description appendix can reduce barriers and costs of replicating published results. It is an important first step toward full scientific reproducibility.

**Q. Does the Artifact Evaluation appendix really impact scientific reproducibility?**

A. A thorough artifact evaluation effort is an effective way to increase the trustworthiness of computational results from special "boutique" platforms. Leadership computing platforms, novel testbeds, and experimental computing environments are of keen interest to the supercomputing community. At the same time, these platforms are often volatile and possess a higher risk of incorrect behavior.

Furthermore, access to these systems is typically limited, making it nearly impossible for most reviewers to independently compute author results. Finally, the volatility of these platforms often make it hard for the authors themselves to recompute their own results in the future, since changes in the environment (compilers, libraries, components, etc.) impact computational results, and there is no way to revert to previous system states.

For all of these reasons, the introduction of upstream setup testing, peri-execution time testing and post-execution analysis can improve confidence that computational results from these special platforms are correct.

**Q. The SC18 review process is double blind. Won't the information in these appendices reveal author identities?**

A. It is possible that the information provided in the appendix could provide reviewers with some evidence of author identities, but it is not necessarily more revealing than self-citations in the bibliography. Listing the software you use does not necessarily mean you develop the software. As with self-references in your text, you should refer to software from a third-person perspective. Finally, if you have any unaddressed concerns about completing appendices for SC18, please contact Mike Heroux ( [maherou@sandia.gov](mailto:maherou@sandia.gov)).

**Q. The Artifacts Available badge description in the ACM website states that "Personal web pages are not acceptable for this purpose". Does SC18 provide a permanent repository as I don't have free access to any repositories beyond my personal website?**

A. No. There are numerous source hosting platforms that provide free or inexpensive hosting.   One of these should be used.

**Q. What kind of recognition do I get for submitting these appendices?**

A. **ACM Artifacts Available Badge:**  An accepted paper with a fully completed Artifacts Description appendix is further eligible for the ACM Artifacts Available Badge if the artifacts listed in the appendix are accessible (downloadable) by anyone without restriction.

A.  **ACM Artifacts Evaluated Badge:**  An accepted paper with fully completed Artifacts Description and Computational Results Analysis appendices is further eligible for the ACM Artifacts Evaluated badge if its artifacts are downloadable and positively evaluated by reviewers.

A. **ACM Replicated Computational Results Badge:**  Accepted papers that contain one or both of these appendices will be considered for inclusion in the SC18 Student Cluster Competition (SCC), where student teams will attempt to replicate the results in the paper. Several papers will be selected, with consent from the authors, as part of the standard review process. Papers will be selected based on their suitability for use in SCC. Papers selected for the SCC will receive the ACM Replicated Computational Results badge.
