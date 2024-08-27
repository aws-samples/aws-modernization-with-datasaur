---
title: "Vector Store Creation" # MODIFY THIS TITLE
chapter: true
weight: 2 # MODIFY THIS VALUE TO REFLECT THE ORDERING OF THE MODULES
---

# Vector Store Creation <!-- MODIFY THIS HEADING -->
Click the **Create new vector store** button.

![Create New Vector Store](/images/create.png) 

Configure your vector store settings.

![Vector Store settings](/images/settings.png) 

The configurations are:

**Name:** Your preferred vector store name

**Vector store provider:** We support two types of vector store provider:

- **Datasaur:** Utilizing the Datasaur provider means Datasaur will handle the embedding process for you.

- **External:** Choosing the External provider allows you to handle the embedding process independently.

**Embedding model:** Your preferred embedding models. Several embedding models that we support by default are:

Amazon Bedrock (served by Datasaur)
- amazon.titan-embed-text-v1
- amazon.titan-embed-image-v1
- amazon.titan-embed-text-v2:0
- cohere.embed-english-v3
- cohere.embed-multilingual-v3

OpenAI (served by Datasaur)
- Text Embedding Ada 002
- Text Embedding 3 Small
- Text Embedding 3 Large

Vertex AI (served by Datasaur)
- textembedding gecko@003
- text-embedding-004
- textembedding-gecko-multilingual@001
- text-multilingual-embedding-002

**Chunk size:** The maximum number of characters that a chunk can contain. The larger the numbers, the bigger each chunk will be, allowing more data to be included within it.

**Overlap:** The number of characters that should overlap between two adjacent chunks. The larger the overlap, the more information each chunk shares with its neighboring chunks.

**Advanced settings:** Additional settings can enhance your data organization by enabling you to provide information about the file using the [File Properties](https://docs.datasaur.ai/llm-projects/vector-store/file-properties) feature.