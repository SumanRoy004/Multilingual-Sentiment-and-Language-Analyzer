# Multilingual Sentiment and Language Analyzer
- This application basically takes the any text or paragraph in any language and detects the sentiment of the language in english and also detects the original language type of given text and also gives the english translation of the given text.
- Here is an finetuned LLM model which is finetuned from the base model unsloth/llama-3.2-3b-instruct-unsloth-bnb-4bit using a sentiment and translated dataset with unsloth library for efficiently finetunning the base model.This finetuned LLM model processes the whole work in the application.
- Finetuned model repository :

     [![Hugging Face Model](https://img.shields.io/badge/HuggingFace%20Model-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Suman2004/lang-trans-sentiment-analyser__finetuned-llama-3.2-3b-instruct-unsloth-bnb-4bit)

- Dataset repository after the processing the raw csv data :

   [![Hugging Face Dataset](https://img.shields.io/badge/HuggingFace%20Dataset-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/datasets/Suman2004/lang-trans-sentiment)

- ## Training Details
- Training graphs are given below

     ![Screenshot (297)](https://github.com/user-attachments/assets/fa1022f4-9416-4c8d-890d-c857a77d1734)

- Run summary is given below
  
     ![Screenshot (296)](https://github.com/user-attachments/assets/60a40172-7852-4ed1-86bb-9e23c45d583c)
  

- ##  User Interface
- This system provides gradio user interface to user.

     ![Screenshot (292)](https://github.com/user-attachments/assets/bca05aa4-be5a-4b0a-9757-52e4a2475a2e)

- Testing with an input:

     ![Screenshot (293)](https://github.com/user-attachments/assets/9b2b660c-2fe6-4b91-873e-7033fce66356)
  

- ## Deployment
- As,we use our own finetuned model so,for loading the model directly and processing the work,we need minimum 10 GB GPU storage which is available in hugging face space but, it is costly.So,that's why we test the model in google collab file.
- After testing our own finetuned model with gradio interface,we used hugging face space for deployment purpose.As huggingface space doesn't provide the GPU in free of cost,but provides CPU basic 2 vCPU 16 GB RAM in free of cost,we deployed this app on CPU basic 2 vCPU 16 GB RAM hardware.But it's performance is very slow.
- It is deployed with Huggingface Space :

  [![Hugging Face Space](https://img.shields.io/badge/HuggingFace%20Space-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Suman2004/Multilingual-Sentiment-and-Language-Analyzer)



