# Fine-Tune-LLM-Model
Use datasets to fine-tune OpenAI Models - supervised fine-tuning

In this project, I fine-tune OpenAI's 'gpt-4.1-nano-2025-04-14' model to make its outputs more truthful: after fine-tuning, the model will be less likely to make up answers, and it will simply answer 'I don't know' for answers that it is not sure about.

#steps:
create dataset in JSONL format

upload dataset containing example prompts and desired outputs

Create a fine-tuning job for a base model using training data

Evaluate results using the fine-tuned model


#User Guide:

If you want to run the project, you should change the API key to your own OpenAI API key, and then you can run it.
