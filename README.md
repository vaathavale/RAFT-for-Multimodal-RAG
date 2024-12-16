 Multimodal Retrieval Augmented Finetuning


The src folder contains:
- The script used for finetuning OPT1.3B
- The code utilized to create the retriever using langchain
- The code utilized to summarize images using LLaVA 1.5
- The pipeline utilized to test responses from the baseline and finetuned models

The data folder contains:
- The data used for the retriever
- The data generated from the RAFT (https://github.com/ShishirPatil/gorilla/tree/main/raft) recipe to finetune OPT1.3B <br>
  The data itself is from https://github.com/allenai/multimodalqa
