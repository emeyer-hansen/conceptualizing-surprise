[_metadata_:author]:- "Emil Niclas Meyer-Hansen"
[_metadata_:date]:- "2026-03-01"
[_metadata_:tags]:- "markdown metadata"
# Conceptualizing Surprise with the Jensen–Shannon distance: A Bayesian Information Theoretical Approach for the Social Sciences

*Emil Niclas Meyer-Hansen*

2026-03-01

A formal (re)conceptualization of surprise is developed by the author for the social sciences in the research paper *Conceptualizing Surprise with the Jensen–Shannon distance: A Bayesian Information Theoretical Approach for the Social Sciences* (see the Abstract below). The paper is currently a work-in-progress. It subscribes to the [*open science standard*](https://www.cos.io/open-science), is partly licensed under the CC BY 4.0 and partly under the GPL-3.0 (see the License below), and it is made freely available in PDF-format.

## Table of Contents
- [Abstract](#abstract)
- [FAQ](#faq)
- [Changelog](#changelog)
- [License](#license)
- [Citation](#citation)

<a id="abstract"></a>
## Abstract

Generally in the social sciences, a result is informally deemed 'surprising' if its associated *p*-value is sufficiently small. This implicit interpretation, however, is both conceptually and mathematically inappropriate, and such misuse of the *p*-value can lead to erroneous conclusions about the novelty of results. To solve that issue, this paper builds on Bayesian inference, Information theory, and considerations specific to the social sciences, to argue for the adoption of a more appropriate conceptualization of surprise as the *relative entropy between prior and posterior knowledge*. Novel to the social sciences, this formal conceptualization enables researchers to appropriately measure surprise as the Jensen-Shannon distance, for which the paper contributes with easily implementable software and a demonstration of its use in relation to empirical data.[©](#license)

**Keywords**: *Surprise; Novelty; Jensen-Shannon distance; JS distance; Jensen-Shannon divergence; JS divergence; Relative entropy; Kullback-Leibler divergence; KL divergence; Distance; Divergence; Dissimilarity; Differential entropy; Entropy; p-value; S-value; Information theory; Bayesian inference*

<a id="faq"></a>
## FAQ
- Where can I download the latest version of the paper? The newest version of the paper is always provided unter the 'Files'-tab and is simply named 'Article.pdf'.
- How can I replicate this paper? The results of the research paper can be replicated in R using the replication files provided in the 'Archive'-folder. Identify the version of the paper that you want to replicate, download the files, specify your working directory and begin executing the code chunks provided in the R HTML File. Note that replication files are only provided from v2026-03-01-13-00 and onwards.

<a id="changelog"></a>
## Changelog
- **2026-03-01 13:00 CEST**
    - [Version 2026-03-01-13-00] - Working paper (Major revisions).
        - Major revisions of multiple sections (e.g., new sections added, missing words added, corrected misspellings)
        - Added 'Discussion' and 'Conclusion'-sections.
        - Replicated results by re-running all analyses of the data.
- **2026-02-07 15:20 CEST**
    - [Version 2026-02-07-15-20] - Working Paper (Minor revisions).
         - Minor revisions (e.g., added missing words, corrected mispellings)
         - Fixed issue in JS function that prevented the user-specified base being used for the logarithmic function.
- **2026-02-01 13:58 CEST**
    - [Version 2026-02-01-13-58] - Working Paper (Revised Release).
         - Added content for the 'Demonstration'-section.
         - Improved existing sections.
- **2026-01-14 15:45 CEST**
    - [Version 2026-01-14-15-45] - Working Paper (Initial Release).

<a id="license"></a>
## License (Addendum)

Except where otherwise indicated, all contents of this document and associated files are licensed under the *Creative Commons Attribution 4.0 International License* ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). All software, including but *not* necessarily limited to, source code, executable code, code snippets, code chunks, algorithms, and/or scripts, attributable to this document and/or any of its associated files are expressly excluded from the foregoing license, and unless otherwise indicated, are instead licensed under the *GNU General Public License, version 3* ([GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html)). By engaging with this document and/or any associated files, which include, but are *not* necessarily limited to, downloading, using, viewing, and/or distributing any of them, in parts or whole, you agree to comply with the applicable license terms for the respective content types.

<a id="citation"></a>
## Citation

Building on Bayesian inference, Information theory, and similar conceptualizations made for other scientific disciplines, this formal conceptualization of surprise as the relative entropy between prior and posterior knowledge, measurable as the Jensen-Shannon distance, is an original (re)conceptualization by Emil Niclas Meyer-Hansen specifically for the social sciences, conceived as part of the research paper associated with this project. For correspondence, contact the author via email: [emil098meyerhansen@gmail.com](mailto:emil098meyerhansen@gmail.com)

Please, if you use, refer to, modify, and/or continue the development of this formal conceptualization of surprise for the social sciences, provide proper reference and citation to its founding author. An example of proper citation is provided below:
```
Meyer-Hansen, E. N. (2026): 'Conceptualizing Surprise with the Jensen–Shannon distance: A Bayesian Information Theoretical Approach for the Social Sciences', Open Science Framework, Working paper (v2026-03-01-13-00). DOI: [10.17605/OSF.IO/GQ6C8](https://doi.org/10.17605/OSF.IO/GQ6C8)
```

For LaTeX users, a BibTeX entry is provided below:
```
@unpublished{,
  title = {Conceptualizing Surprise with the Jensen–Shannon distance: A Bayesian Information Theoretical Approach for the Social Sciences},
  author = {Emil Niclas Meyer-Hansen},
  publisher = {Open Science Framework},
  year = {2025},
  doi = {10.17605/OSF.IO/GQ6C8},
  pubstate = {Working Paper (v2026-03-01-13-00)}
}
```
