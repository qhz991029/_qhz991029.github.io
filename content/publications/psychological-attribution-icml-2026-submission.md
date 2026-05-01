---
id: psychological-attribution-icml-2026-submission
title: "Modeling Attributional Style at Scale: A Dataset and Analysis for Psychological Attribution Assessment and Reframing"
authors:
  - Qiang Zhou
  - Hanzhen Zhu
  - Pan Wang
  - Rui Tu
  - Huaizhi Qu
  - Zhuoran Wang
  - Xin Hu
  - Lei Li
  - Tianlong Chen
  - Jingtong Hu
venue: ICML 2026
venueType: conference
year: 2026
status: accepted
links:
  paper: "https://openreview.net/forum?id=qgyEEb6wkh"
---

According to the reformulated version of Learned Helplessness theory, an individual who experiences uncontrollable negative events may subsequently develop a negative attributional style, thereby exhibiting greater susceptibility to depressive symptoms. This depressogenic attributional style not only contributes to depressive symptoms but also represents a malleable target for cognitive therapy. Despite its theoretical and practical significance, computational research on attributional cognition remains underexplored due to the lack of large-scale, high-quality datasets and robust evaluation protocols. In this work, we introduce the Attributional Style Transfer Dataset together with dedicated evaluation metrics, the first benchmark designed to model, assess, and reframe attributional explanations at scale. Constructed via a Prevent-Filter-Validate pipeline that integrates LLM-based generation with specialist validation, ASTD contains 42,000 real-world events paired with psychologically grounded attributions spanning seven styles. Using this dataset, we address scalable assessment of attributional style and attributional reframing with automatic evaluation metrics to quantify psychological validity. We further leverage these metrics to construct a preference dataset, fine-tuning LLMs with DPO and achieving substantial gains in reframing quality.
