# Lightweight-Fine-Tuning-Project

## UDACITY's project for GENERATIVE AI FUNDAMENTALS

Load a pre-trained model and evaluate its performance
Perform parameter-efficient fine-tuning using the pre-trained model
Perform inference using the fine-tuned model and compare its performance to the original model

PEFT technique: LORA
Model: distilbert-base-uncased
Evaluation approach: Hugging Face Trainer class
Fine-tuning dataset:fancyzhx/amazon_polarity

Loading the model
Evaluating the model
  Perform an initial evaluation of the model the chosen sequence classification task. 

Performing Parameter-Efficient Fine-Tuning
  Creating a PEFT config
  Create a PEFT config with appropriate hyperparameters for your chosen model.

Creating a PEFT model
  Using the PEFT config and foundation model, create a PEFT model.

Training the model
  Using the PEFT model and dataset, run a training loop with at least one epoch.

Saving the trained model

Performing Inference with a PEFT Model
  Loading the model
  Using the appropriate PEFT model class, load your trained model.

Evaluating the model
  Repeat the previous evaluation process, this time using the PEFT model. Compare the results to the results from the original foundation model.


Directly from the Project Workspace (recommended)
Uploading a zip file
Sharing a GitHub repository link (must be a public link)
Your submission must include:

Your Jupyter notebook file (.ipynb )
Your saved weights
