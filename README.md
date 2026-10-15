# Beyond Predictive Performance: Detecting Internal Model Change in Federated Insider-Threat Evaluation

## The code designed for this work will be available once the final paper is published

### Abstract (summary)

Federated insider-threat models may change internally as behavioural data arrive, even when predictive performance changes only modestly. This study reconstructs and evaluates the Federated Incremental Insider Threat Benchmark Protocol, combining chronological federated training, a fixed evaluation reference, predictive measures, prediction-distribution monitoring and classifier-representation analysis. A synthetic CERT R6.2 reconstruction contained 1,394,010 user-days and 23 behavioural features. Five non-overlapping clients trained through ten increments, with 206,926 user-days held as a fixed evaluation reference. A frozen autoencoder supplied 16-dimensional embeddings, auxiliary Isolation Forest anomaly labels supported training, and genuine incident labels provided the principal evaluation target. Across five classifier seeds, mean area under the receiver operating characteristic curve (ROC-AUC) began at 0.6643, fell to 0.6565 at the first increment, and recovered to 0.6907. Mean prediction-distribution divergence from baseline reached 3.4697 at the final increment, while mean hidden-centroid displacement reached 9.4215. These measures use different scales and describe complementary aspects of model evolution. Strong auxiliary anomaly performance did not imply strong malicious-insider detection. The findings demonstrate how a final predictive score can conceal early deterioration, subsequent recovery and continuing internal change. Generalisation is limited by synthetic data, sparse incident labels, configuration dependence and reuse of the evaluation reference during development. The contribution is a reproducible evaluation structure, not a new detector or evidence that observed model movement proves real-world concept drift.

### Code and research materials

[FI-ITBP code and reproducibility repository](https://github.com/lhourany/fi-itbp-reproducibility)

The linked repository is currently private and can only be accessed by authorised collaborators. Other visitors may see a GitHub 404 page until the code is released upon publication. This public repository provides the research summary and a stable link for the dissertation and journal manuscript.
