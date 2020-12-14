# CourseProject (Text Classification)

# Overview
The project I chose was the sarcasm detection competition.

I successfully beat the baseline by training a PyTorch BERT model using the Huggingface transformers library. I first researched what types of models could be used for this manner of text classification and found that the Huggingface library (https://huggingface.co/) had multiple pretrained models to suit this goal. Some minor data cleanup and preprocessing on the training/test data sets, along with concatinating the immediate context with the response allowed me to beat the baseline.

# Libraries/Languages

- Python
- Pytorch
- Huggingface transformers
- Pandas
- SKLearn

# Implementation

I developed the entire project within a Google Colab (https://colab.research.google.com/) notebook. I used the free tier for all development and the final model training. I recommend opening the ipynb in Colab to run the code without needing to configure any of the libraries locally.

# Usage

1. Open CS410Project.ipynb in Google Colab (https://colab.research.google.com/)
2. The data storage for a Google Colab workspace is ephemeral, so the train.jsonl and test.jsonl files must be uploaded to the workspace storage each time.
3. (Optional) For faster model training, click Edit -> Notebook Settings, then set the Hardware Accelerator to 'GPU' inside the popup. This was available for me using the free tier of Colab during development. The code will default to CPU computation if this is not done and the model will take longer to train.
4. Run all code blocks in order. The file `answer.txt` will be created in the workspace for download. I used 5 epochs for training and it generated predictions that beat the baseline.

# Presentation

I did not have time to do a presentation.
