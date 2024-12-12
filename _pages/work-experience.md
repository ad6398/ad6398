---
layout: archive
# title: "Work Experience"
permalink: /work-experience/
author_profile: true
---
{% include base_path %}

# Work Experience

## Machine Learning Engineer Intern at *PineGap.ai*
**May, 2024 - August, 2024**

- Designed high-level and low-level components of an AI assistant for equity research and financial market analysis. I was the first AI hire, owned and built everything from scratch. 
- Developed end-to-end components of a keyword-guided retrieval and search engine. Used BM25, Elastic Search, dense vector search, fine-tuned Splade, and ColBERT models for query augmentation and candidate reranking.
- Built an advanced agentic RAG framework with CI/CD pipelines for query understanding, document ingestion, and knowledge graph building to support Q&A over the past 10 years of financial documents from S&P 2000 companies.
- Developed and containerized microservices to fine-tune and serve LLMs (LLaMa-3, Phi-3 and Mixtral) as APIs using Docker and Kubernetes. Employed techniques like quantization, flash attention, LoRA, data and model parallelism for efficient fine-tuning on GPUs. Utilized vLLM, Paged-attention, Kafka, and Redis for faster LLM inference service.


## Software Engineer, Machine Learning at *Instabase*
**January 2022 - August 2023**

- Integrated Large Language Models, Retrieval Augmented Generation (RAG), and Generative AI capabilities into Instabase’s platform, including model inference service, regression, and load-testing framework.
- Designed and Implemented an asynchronous model serving platform using asynchronous workers, RabbitMQ, multi-level caching, and sticky routing, along with hardware acceleration (ONNX) and model prunning, to reduce inference time by 40% in a compute-limited Kubernetes environment. Built a pipeline to detect format and content drift in documents.
- Enhanced OCR service for improved document parsing and digitization using the LayoutLM model for better table extraction by 60%. Developed an algorithm to detect and process vertical text in PDFs.

## Software Engineer II at *Walmart Global Tech India*
**August 2020 — December 2021**

- Implemented the entity embedding technique for sparse categorical values, improving the accuracy of existing forecasting systems by 17% and reducing inference time by 15%. This also minimized the effort required for feature engineering.
- Enhanced the gradient boosting algorithm to incorporate feedback from distribution center managers while calculating errors to form decision trees. Implemented weighted loss to penalize misclassifications of perishable items, such as fruits and dairy products, more heavily.

## Google Summer of Code, Developer at *AOSSIE Org.*
**May 2019 – August 2019**

- Developed a Google Chrome extension utilizing natural language processing (NLP) to detect toxic comments, clickbait, and fake news on news websites and social media platforms like Facebook and Twitter.
- Trained a stance detection model for fake news classification and implemented a backend service using Flask for model inference. Designed a three-level cache system to optimize latency and avoid duplicate inference requests.

## Applied Research Intern at *Genesys*
**May 2019 – July 2019**

- Implemented a passage ranking algorithm to boost the accuracy of the in-house Question and Answer services’ model on client datasets.
- Created a framework to train AllenNLP’s machine reading comprehension models on in-house medical data as part of a client’s proof of concept (POC) and proposed its integration with the homegrown Chat Bot.
