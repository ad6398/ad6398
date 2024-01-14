---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **New York University - Courant Institute Of Mathematical Sciences**
  *Master of Science, Computer Science*
  Sep 2023 - May 2025
  Subjects: Deep Learning, Large Language and Vision Models, Computer Vision, Operating Systems.
* **Indian Institute Of Technology (ISM), Dhanbad**
  *Bachelor of Technology, Computer Science and Engineering*
  July 2016 — April 2020
  Major Subjects: Data Structures, Algorithms, Object Oriented Programming, Operating Systems, Database Management and Systems, Distributed Systems, Discrete Mathematics, Calculus.

Work experience
======
* Software Engineer, Machine Learning at  *Instabase*
  * January 2022 - August 2023
  * Designed and implemented Model inference service, Regression and load-testing framework to integrate Large-Language-Models and Generative AI capabilities into Instabase’s platform.
  * Devised a model drift detection pipeline that uses layout change detectors to detect format drift and uses Least-Squares Density Difference and Maximum Mean Discrepancies on document embedding to catch content drift in the documents.
  * Designed and implemented the async Model service, which combines async workers, rabbit-MQ, two levels of caching, and sticky routing techniques to improve inference time by 40% on a compute-limited Kubernetes environment.

* Software Engineer II at *Walmart Global Tech India*
  * August 2020 — December 2021
  * Implemented the entity embedding technique for sparse categorical values, which improved the accuracy of the existing forecasting systems by 17% and reduced the inference time by 15%. This also reduced the effort required for feature engineering.
  * Tweaked the gradient boosting algorithm to incorporate the feedback of the distribution center’s manager while calculating errors to form decision trees and implemented weighted loss to penalize misclassifications of perishable items such as fruits and dairy products more heavily.
  
* Google Summer Of Code, Developer at *AOSSIE Org.*
  * May 2019 – Aug 2019
  * Developed a Google Chrome extension that uses natural language processing (NLP) to detect toxic comments, clickbait, and fake news on news websites and social media platforms like Facebook and Twitter. Trained a stance detection model for fake news classification and implemented a backend service using Flask for model inference. Designed a three-level cache system to optimize latency and avoid duplicate inference requests.
* Applied Research Intern at *Genesys*
  * May 2019 – July 2019
  * Implemented passage ranking algorithm to boost the accuracy of in-house Question and Answer services’ model on some client data sets.Created a framework to train AllenNLP’s machine reading comprehension models on in-house medical data as part of a client’s POC and proposed its integration with the homegrown Chat Bot.
  
Skills
======
* **Languages**: Python, C, C++, SQL
* **Tools & Frameworks**: GIT, AWS, GCP, Airflow, Pytorch, Tensorflow, Pandas, NumPy, Docker, K8s, Langchain
  
* **Machine Learning Techniques**: Natural Language Processing, Transformers, Keyphrase Extraction and Generation, Sequence tagging, Question-Answering, Summarization, Code-Switching, Large Language Models, etc.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

  

