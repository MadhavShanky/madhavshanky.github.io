---
abstract: We study linear mixed models in settings where only a small subset of clusters depart meaningfully from the population mean. We cast estimation as a mixed-integer optimization problem that imposes ℓ0 sparsity on random effects while jointly estimating fixed effects, yielding exact zeros for many clusters and interpretable effect estimates for those retained. The formulation admits certified near-optimal solutions at practical scales using modern MIO solvers. Operating characteristics are examined in simulations spanning two regimes; approximately Gaussian random effects and heterogeneous settings in which deviations are concentrated in a few clusters. When the Gaussian specification holds, the proposed estimator performs comparably to Gaussian mixed models for fixed-effect estimation and prediction; when heterogeneity is sparse, it improves estimation accuracy and reduces test error on held-out clusters by focusing attention on atypical units. Prediction is evaluated using a cluster-blocked validation scheme, and we outline a supervised mapping from cluster-level features to predicted random effects to support prediction for new clusters. Two applications demonstrate the approach. Using New York State hospital-acquired infection data for 2019 hysterectomy, the method recovers the hospitals flagged by public reporting while producing a sparse set of hospital effects. In a student performance dataset, it identifies adjusted high- and low-performing students that are not evident from raw scores. A brief protein expression example appears in the Supplement. These results suggest that MIO-based sparsity on random effects is a useful complement to classical mixed-model analysis when the goal is to flag atypical units and improve prediction for new clusters.
authors:
- admin
- Intekhab Hossain
- Tom Chen
date: "2025-11-09T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2302.03157"
featured: false
#projects:
#- internal-project
publication: "Preprint"
publication_short: ""
publication_types:
- article
publishDate: "2025-11-09T00:00:00Z"
#slides: example
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Source Themes
title: A distribution-free mixed-integer optimization approach to hierarchical modelling of clustered and longitudinal data
url_code: ""
url_dataset: ""
url_pdf: https://madhavshanky.github.io/uploads/clust-mio.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
