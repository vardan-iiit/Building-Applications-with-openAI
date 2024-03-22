# Chatbot Language Model Tuning

This project involves fine-tuning the GPT-2 Language Model for chatbot applications using a custom dataset. The code provided allows for the training and inference of a chatbot language model.

## Prerequisites

Make sure you have the required packages installed. You can install them using:


Clone the repository and navigate to the project directory: git clone https://github.com/vishal20265/chatBot.git
cd your-repository

# Usage

To train the chatbot language model, run the following command:
python train_chatbot_model.py

The training script reads the chatbot dataset from a JSON file (chat_data.json in this example) and fine-tunes the GPT-2 model. The trained model state is saved to model_state.pt.

# Customization
Feel free to customize the code based on your requirements. You can adjust hyperparameters, modify the dataset loading process, or experiment with different GPT-2 model variants.

# Dataset
The datset consist of List which have the instruction of the recipe. It have almost 10000 recipe with custom id.

# Contributing
If you'd like to contribute to this project, follow the guidelines in the CONTRIBUTING.md file. Contributions, bug reports, and feature requests are welcome.


LLM model tuning for own dataset 
