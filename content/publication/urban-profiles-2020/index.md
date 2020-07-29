---
title: "Protein Profiles: Biases and Protocols"
date: 2020-06-14
publishDate: 2020-07-21T20:40:40.130424Z
authors: ["Gregor Urban", "Mirko Torrisi", "Christophe N. Magnan", "Gianluca Pollastri", "Pierre Baldi"]
publication_types: ["3"]
abstract: "The use of evolutionary profiles to predict protein secondary structure, as well as other protein structural features, has been standard practice since the 1990s. Using profiles in the input of such predictors, in place or in addition to the sequence itself, leads to significantly more accurate predictors. While profiles can enhance structural signals, their role remains somewhat surprising as proteins do not use profiles when folding in vivo. Furthermore, the same sequence-based redundancy reduction protocols initially derived to train and evaluate sequence-based predictors, have been applied to train and evaluate profile-based predictors. This can lead to unfair comparisons since profile may facilitate the bleeding of information between training and test sets. Here we use the extensively studied problem of secondary structure prediction to better evaluate the role of profiles and show that: (1) high levels of profile similarity between training and test proteins are observed when using standard sequence-based redundancy protocols; (2) the gain in accuracy for profile-based predictors, over sequence-based predictors, strongly relies on these high levels of profile similarity between training and test proteins; and (3) the overall accuracy of a profile-based predictor on a given protein dataset provides a biased measure when trying to estimate the actual accuracy of the predictor, or when comparing it to other predictors. We show, however, that this bias can be avoided by implementing a new protocol (EVALpro) which evaluates the accuracy of profile-based predictors as a function of the profile similarity between training and test proteins. Such a protocol not only allows for a fair comparison of the predictors on equally hard or easy examples, but also completely removes the need for selecting arbitrary similarity cutoffs when selecting test proteins. The EVALpro program is available for download from the SCRATCH suite (http://scratch.proteomics.ics.uci.edu)."
featured: false
publication: "*bioRxiv*"
url_pdf: "https://www.biorxiv.org/content/10.1101/2020.06.13.148718v1.full.pdf"
doi: "10.1101/2020.06.13.148718"
url_code: "http://download.igb.uci.edu/#evalpro"
---

