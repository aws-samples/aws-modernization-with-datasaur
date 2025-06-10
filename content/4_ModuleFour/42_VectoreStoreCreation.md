---
title: "Knowledge Base Creation" # MODIFY THIS TITLE
chapter: true
weight: 2 # MODIFY THIS VALUE TO REFLECT THE ORDERING OF THE MODULES
---

# Knowledge Base Creation <!-- MODIFY THIS HEADING -->
Click the **Create new Knowledge Base** button.

![Create New Knowledge Base](/images/createkb.png) 

Upload your file and select your embedding model.

![Knowledge Base settings](/images/kbconfig.png) 

Here you will be able to decide embedding model, chunk size, and the overlap of your chunks. After you have chosen all three options, select the “Process File(s) button.

The configurations are:


**Embedding model:** Your preferred embedding models. Several embedding models that we support by default are:

OpenAI (served by Datasaur)
- text-embedding-ada-002
- text-embedding-3-small
- text-embedding-3-large
- Text Embedding Ada 002
- Text Embedding 3 Small
- Text Embedding 3 Large

Amazon Bedrock (served by Datasaur)
- amazon.titan-embed-text-v1
- amazon.titan-embed-image-v1
- amazon.titan-embed-text-v2:0
- cohere.embed-english-v3
- cohere.embed-multilingual-v3

Vertex AI (served by Datasaur)
- textembedding-gecko@003
- text-embedding-004
- textembedding-gecko-multilingual@001
- text-multilingual-embedding-002
 
**Chunk size:** The maximum number of characters that a chunk can contain. The larger the numbers, the bigger each chunk will be, allowing more data to be included within it.

**Overlap:** The number of characters that should overlap between two adjacent chunks. The larger the overlap, the more information each chunk shares with its neighboring chunks.

**Advanced settings:** Additional settings can enhance your data organization by enabling you to provide information about the file using the [File Properties](https://docs.datasaur.ai/llm-projects/vector-store/file-properties) feature.