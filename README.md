# Finetuning_Llama_Model


**This project demonstrates training an LLM model using the Lamini library. The training pipeline involves loading a dataset (lamini_docs.jsonl), tokenizing the data, and fine-tuning the model (EleutherAI/pythia-70m). The trained model can be used for inference to generate responses based on input queries.** 

## Steps

1. **Load Data** – Import `lamini_docs.jsonl` containing questions and answers.  
2. **Choose Base Model** – Use `EleutherAI/pythia-70m` as the foundation for training.  
3. **Tokenize & Train** – Process the dataset and fine-tune the model using transformers.  
4. **Inference** – Generate answers using the trained model.  
