---
title: "Improving the assessment of deep learning models in the context of drug-target interaction prediction"
date: 2022-03-31
publishDate: 2022-04-21T20:40:40.131939Z
authors: ["Mirko Torrisi", "Antonio de la Vega de Leon", "Guillermo Climent", "Remco Loos", "Alejandro Panjkovich"]
publication_types: ["1"]
abstract: "Machine Learning techniques have been widely adopted to predict drug-target interactions, a central area of research in early drug discovery. These techniques have shown promising results on various benchmarks although they tend to suffer from poor generalization. This is typically related to very sparse and nonuniform datasets available, which limits the applicability domain of Machine Learning techniques. Moreover, widespread approaches to split datasets (into training and test sets) treat a drug-target interaction as an independent entities, when in reality the drug and target involved may take part in other interactions, breaking apart the assumption of independence. We observe that this leads to overly optimistic test results and poor generalization of out-of-distribution samples for various state-of-the-art sequence-based Machine Learning models for drug-target prediction. We show that previous approaches to reduce bias in binding datasets focus on drug or target information only and, thus, lead to similar pitfalls. Finally, we propose a minimum viable solution to evaluate the generalization capability of a Machine Learning model based on the systematic separation of test samples with respect to drugs and targets in the training set, thus discerning the three out-of-distribution scenarios seen at test time: (1) drug or (2) target present in the training set, or neither (3)."
featured: false
publication: "*ICLR2022 Machine Learning for Drug Discovery*"
tags: ["interpretability", "generalization", "drug-target interactions", "benchmark"]
url_pdf: "https://openreview.net/pdf?id=3avOwM2sF1"
doi: "10.1101/2022.04.20.488898"
---

