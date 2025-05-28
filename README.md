# OT-networkAttacksDatasets

This repository provides supplementary matertial associated with the paper

### "Systematic review and characterisation of malicious industrial network traffic datasets

submitted to the **International Journal of Information Security**.

## tldr:

The paper systematically reviews publicly available network traffic capture-based datasets, including categorisation of contained attack types, review of metadata, and statistical as well as complexity analysis.


## Repository content:

 - **'ComplexityAnalysis.csv'**  -- A csv-file containing the detailed results of the complexit calculation. For each of the labelled (ML-ready) datasets identified in the above paper, we provide the results returned by the Python tool ``problexity`` which computes 21 individual complexity metrics. [https://problexity.readthedocs.io/en/latest/] The final complexity scores are also provided inside the paper.

 - **'Feature Analysis'** --  A folder containing the complete reseults of the feature analysis performed on three exemplary datastes of low, medium, and high complexity. Due to space limitations only the most important features are included in the paper.
