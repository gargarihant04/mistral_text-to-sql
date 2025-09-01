# Fine-Tuning Mistral-7B on Spider Dataset for Text-to-SQL

Internship Project at Indian Institute of Remote Sensing (IIRS),ISRO,Dehradun

This project focuses on fine-tuning the Mistral-7B large language model using the Spider dataset for Text-to-SQL tasks. The fine-tuning process is optimized with LoRA (Low-Rank Adaptation) to make training efficient and resource-friendly.  

---

##  Project Overview
- Objective: Enable Mistral-7B to generate accurate SQL queries from natural language questions.  
- Dataset: [Spider Dataset](https://yale-lily.github.io/spider) – a large-scale, complex, cross-domain Text-to-SQL benchmark.  
- Approach:
  - Preprocessed dataset for compatibility with Hugging Face `datasets` library.  
  - Applied **LoRA fine-tuning** for parameter-efficient training.  
  - Evaluated model on query accuracy & SQL correctness.  

---

## Tech Stack
- Programming Language: Python  
- Frameworks & Libraries:  
  - [Transformers](https://huggingface.co/docs/transformers/index)  
  - [PEFT (LoRA)](https://github.com/huggingface/peft)  
  - [Datasets](https://huggingface.co/docs/datasets/)  
  - PyTorch  
- Infrastructure: AWS EC2 with GPU support  
