---
title: "Protein profiles: Biases and protocols"
date: 2020-08-27
publishDate: 2020-08-28T20:40:40.130424Z
authors: ["Gregor Urban", "Mirko Torrisi", "Christophe N. Magnan", "Gianluca Pollastri", "Pierre Baldi"]
publication_types: ["2"]
abstract: "The use of evolutionary profiles to predict protein secondary structure, as well as other protein structural features, has been standard practice since the 1990s. Using profiles in the input of such predictors, in place or in addition to the sequence itself, leads to significantly more accurate predictions. While profiles can enhance structural signals, their role remains somewhat surprising as proteins do not use profiles when folding in vivo. Furthermore, the same sequence-based redundancy reduction protocols initially derived to train and evaluate sequence-based predictors, have been applied to train and evaluate profile-based predictors. This can lead to unfair comparisons since profiles may facilitate the bleeding of information between training and test sets. Here we use the extensively studied problem of secondary structure prediction to better evaluate the role of profiles and show that: (1) high levels of profile similarity between training and test proteins are observed when using standard sequence-based redundancy protocols; (2) the gain in accuracy for profile-based predictors, over sequence-based predictors, strongly relies on these high levels of profile similarity between training and test proteins; and (3) the overall accuracy of a profile-based predictor on a given protein dataset provides a biased measure when trying to estimate the actual accuracy of the predictor, or when comparing it to other predictors. We show, however, that this bias can be mitigated by implementing a new protocol (EVALpro) which evaluates the accuracy of profile-based predictors as a function of the profile similarity between training and test proteins. Such a protocol not only allows for a fair comparison of the predictors on equally hard or easy examples, but also reduces the impact of choosing a given similarity cutoff when selecting test proteins. The EVALpro program is available in the SCRATCH suite ( www.scratch.proteomics.ics.uci.edu) and can be downloaded at: www.download.igb.uci.edu/#evalpro."
featured: false
publication: "*Computational and Structural Biotechnology Journal*"
tags: ["Machine learning", "Protein structure prediction", "Deep learning"]
url_pdf: "https://www.sciencedirect.com/science/article/pii/S2001037020303688"
doi: "10.1016/j.csbj.2020.08.015"
url_code: "http://download.igb.uci.edu/#evalpro"
---

