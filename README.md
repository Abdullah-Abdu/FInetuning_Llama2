# Finetuning_Llama2


**This project demonstrates training a Llama-based model using the Lamini library.**  

## Steps

1. **Load Data** – Import `lamini_docs.jsonl` containing questions and answers.  
2. **Choose Base Model** – Use `EleutherAI/pythia-70m` as the foundation for training.  
3. **Tokenize & Train** – Process the dataset and fine-tune the model using transformers.  
4. **Inference** – Generate answers using the trained model.  
