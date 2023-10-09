---
date: "2022-02-27"
external_link: ""
summary: 'We create a mixed-integer optimization (MIO) approach for doing cluster-aware regression, i.e. linear regression that takes into account the inherent clustered structure of the data, and compare its efficacy to linear mixed effects regression'
tags:
- all
- misc
title: 'A distribution-free mixed-integer optimization approach to hierarchical modelling of clustered and
longitudinal data'
url_code: "https://github.com/Madhav1812/cluster-mio"
url_pdf: "https://arxiv.org/pdf/2302.03157.pdf"
url_slides: ""
url_video: ""
---



_In collaboration with Intekhab Hossain and Tom Chen_



We create a mixed-integer optimization (MIO) approach for doing cluster-aware regression, i.e. linear regression that takes into account the inherent clustered structure of the data. We compare to the linear mixed effects regression (LMEM) which is the most used current method, and design simulation experiments to show superior performance to LMEM in terms of both predictive and inferential metrics in silico. Furthermore, we show how our method is formulated in a very interpretable way; LMEM cannot generalize and make cluster-informed predictions when the cluster of new data points is unknown, but we solve this problem by training an interpretable classification tree that can help decide cluster effects for new data points, and demonstrate the power of this generalizability on a real protein expression dataset.