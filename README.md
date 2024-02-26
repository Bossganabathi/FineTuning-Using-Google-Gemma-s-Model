# Fine tuning google gemma model
Fine tune this model by using our own custom dataset which is available in huggingface. 
The dataset name: Abirate/english_quotes
Link dataset: https://huggingface.co/datasets/Abirate/english_quotes
For this project import gemma-2b model. This model is 2 billion parameter model.
To access this model in huggingface first need to accept the term and condition.
Then access the token in huggingface, add in HF_TOKEN
Using LoraConfig method to fine tune the model.
