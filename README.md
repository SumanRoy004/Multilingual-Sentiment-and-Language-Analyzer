# Multilingual Sentiment and Language Analyzer
- This application basically take the any text or paragraph in any language and detect the sentiment of the language in english and also detect the original language type of given text and also gives the english translation of the given text.
- Here is an finetuned LLM model which is finetuned from the base model unsloth/llama-3.2-3b-instruct-unsloth-bnb-4bit using a sentiment and translated dataset with unsloth library for efficiently finetunning the base model.This finetuned LLM model processes the whole work in the application.
- Model repository:

     [![model repository](https://img.shields.io/badge/model_repository-1DA1F2?style=for-the-badge&logo=modelrepository&logoColor=white)](https://huggingface.co/Suman2004/lang-trans-sentiment-analyser__finetuned-llama-3.2-3b-instruct-unsloth-bnb-4bit)

- Dataset repository after the processing the raw csv data:

  [![dataset_repository](https://img.shields.io/badge/dataset_repository-1DA1F2?style=for-the-badge&logo=Sdatasetrepository&logoColor=white)](https://huggingface.co/datasets/Suman2004/lang-trans-sentiment)

- ##  User Interface
- This system provides gradio user interface to user.

     ![Screenshot (292)](https://github.com/user-attachments/assets/bca05aa4-be5a-4b0a-9757-52e4a2475a2e)

- Testing with an input:

     ![Screenshot (293)](https://github.com/user-attachments/assets/9b2b660c-2fe6-4b91-873e-7033fce66356)

- ## Deployment
- As,we use our own finetuned model so,for loading the model directly and processing the work,we need minimum 10 GB GPU storage which is available in hugging face space but, it is costly.So,that's why we test the model in google collab file.
- After testing our own finetuned model with gradio interface,we used hugging face space for deployment purpose.As huggingface space doesn't provide the GPU in free of cost,but provides CPU basic 2 vCPU 16 GB RAM in free of cost,we deployed this app on CPU basic 2 vCPU 16 GB RAM hardware.But it's performance is very slow.
- Huggingface Space link:

   [![Huggingface Space](https://img.shields.io/badge/Huggingface_Space-1DA1F2?style=for-the-badge&logo=Shuggingfacespace&logoColor=white)](https://huggingface.co/spaces/Suman2004/Multilingual-Sentiment-and-Language-Analyzer)


