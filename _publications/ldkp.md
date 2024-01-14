---
title: "LDKP - A Dataset for Identifying Keyphrases from Long
Scientific Documents"
collection: publications
permalink: /publication/ldkp
excerpt: 'A Dataset for Identifying Keyphrases from Long
Scientific Documents'
date: 2022-10-17
venue: 'DL4SR’22: Workshop on Deep Learning for Search and Recommendation, co-located with the 31st ACM International Conference on
Information and Knowledge Management (CIKM)'
paperurl: 'https://ceur-ws.org/Vol-3317/Paper9.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Identifying keyphrases (KPs) from text documents is a fundamental task in natural language processing and information
retrieval. Vast majority of the benchmark datasets for this task are from the scientific domain containing only the document
title and abstract information. This limits keyphrase extraction (KPE) and keyphrase generation (KPG) algorithms to identify
keyphrases from human-written summaries that are often very short (≈ 8 sentences). This presents three challenges for
real-world applications: i) human-written summaries are unavailable for most documents, ii) a vast majority of the documents
are long, and iii) a high percentage of KPs are directly found beyond the limited context of the title and the abstract. Therefore,
we release two extensive corpora mapping KPs of ≈ 1.3𝑀 and ≈ 100𝐾 scientific articles with their fully extracted text
and additional metadata including publication venue, year, author, field of study, and citations for facilitating research on
this real-world problem. Additionally, we also benchmark and report the performances of different unsupervised as well as
supervised algorithms for keyphrase extraction on long scientific documents. Our experiments show that formulating keyphrase
extraction as a sequence tagging task with modern transformer language models capable of processing long text sequences such
as longformer has advantages over the traditional algorithms, not only resulting in better performances in terms of F1 metrics
but also in learning to extract optimal number of keyphrases from the input documents.

[Download paper here](https://ceur-ws.org/Vol-3317/Paper9.pdf)

<!-- Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->