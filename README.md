# Game Ad Generation with BART and LoRA
This repository features a Jupyter notebook focused on fine-tuning a BART model to generate persuasive game advertisements. It leverages LoRA for efficient training on a Steam product descriptions dataset, creating engaging ad copy from game genres, categories, and a short description. The notebook includes data preprocessing, Hugging Face Trainer API usage, FP16 training, and an ad generation function.

# How to Use:
Clone the Repository and install all the dependendencies.

Run the notebook bart_game_ad.ipynb in a Jupyter environment (e.g., Jupyter Lab, Google Colab).

The notebook will load the BART model and tokenizer.

It will then download and preprocess the dataset.

LoRA configuration will be applied to the model.

The model will be trained for 3 epochs.

Finally, you can use the generate_ad function to create new game advertisements.

# Example Generated Ads:
The notebook includes examples of generated ads with various inputs:

RPG, Fantasy Game: An ad for an epic journey through a magical realm.

Strategy, Simulation Game: An ad for building a futuristic city with intricate management.

Action, Indie Platformer: An ad for a pixelated Metroidvania experience.
