# A Fine-Tuned Large Language Model for Improved Click-Bait Title Classification
 Our proposed methodology utilizes a fine-tuned large language model to detect clickbait titles with high accuracy, requiring only a limited dataset of clickbait titles for fine-tuning.

Requirements : openai_api_key,google colab. 

The total fine-tuning process can be done by following the steps and executing the code in 'Fine-tuned_ADA_LLM_Classification_of_Clickbaits.ipynb' file.

The dataset for finetuning for each type of model can be obtained from particular model folders.

Each model and it's Description:

Model 1.2 : We fine-tuned Ada LLM with 200 data samples of click-bait and non-click bait titles, resulting in a new model with 4 epochs.
Model 1.4 :  We used Model 1 to fine-tune it with another 200 data samples, resulting in Model 2 with 4 epochs.
Model 1.6 :  Using Model 2 and another 200 data samples, we fine-tuned it to obtain Model 3 with 4 epochs.
Model 1.8 : We fine-tuned Model 3 with another 200 data samples to create Model 4 with 4 epochs.
Model 2 : Finally, we fine-tuned Model 4 with another 200 data samples to generate Model 5 with 4 epochs.
Model C : We have fine-tuned Ada LLM with 1000 data samples with 20 epochs.
Model  D : We have fine-tuned Ada LLM with 1000 data samples with 4 epochs.

The test_dataset.csv can be obtained from test_data folder.







