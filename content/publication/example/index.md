---
abstract: While the advanced machine learning algorithms are effective in load
  forecasting, they often suffer from low data utilization, and hence their
  superior performance relies on massive datasets. This motivates us to design
  machine learning algorithms with improved data utilization. Specifically, we
  consider the load forecasting for a new user in the system by observing only
  few shots (data points) of its energy consumption. This task is challenging
  since the limited samples are insufficient to exploit the temporal
  characteristics, essential for load forecasting. Nonetheless, we notice that
  there are not too many temporal characteristics for residential loads due to
  the limited kinds of human lifestyle. Hence, we propose to utilize the
  historical load profile data from existing users to conduct effective
  clustering, which mitigates the challenges brought by the limited samples.
  Specifically, we first design a feature extraction clustering method for
  categorizing historical data. Then, inheriting the prior knowledge from the
  clustering results, we propose a two-phase Long Short Term Memory (LSTM) model
  to conduct load forecasting for new users. The proposed method outperforms the
  traditional LSTM model, especially when the training sample size fails to
  cover a whole period (i.e., 24 hours in our task). Extensive case studies on
  two real-world datasets and one synthetic dataset verify the effectiveness and
  efficiency of our method.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Qiyuan Wang
  - Zhihui Chen
  - Chenye Wu
author_notes:
  - Equal contribution
  - Equal contribution
  - Corresponding author
publication: In *IEEE Sustainable Power and Energy Conference, 2021*
summary: The contribution of this paper to load forecasting is the introduction
  of Few-shot learning method, which uses prior knowledge from historical user
  data to predict scarce samples more accurately than traditional forecasting
  methods
url_dataset: ""
url_project: ""
publication_short: In *ISPEC2021*
url_source: ""
url_video: ""
title: Clustering Enabled Few-shot Load Forecasting
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: structure.jpg
date: 2021-12-22T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
