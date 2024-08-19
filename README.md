# nextedge-morpheus

Synthetic Data Generation Module:

This notebook automates the generation of synthetic data for various categories of social media posts, which could be useful for training or testing machine learning models.

Initialization:

The OpenAI client is initialized using an API key and a base URL (api.aimlapi.com).

Prompts and Categories:

A list of prompts with corresponding categories is defined, such as generating a positive social media post, a spammy comment, a neutral statement, and a misleading news headline.

Synthetic Data Generation:

For each prompt-category pair, the code generates 100 samples using the meta-llama/Meta-Llama-3.1-70B-Instruct-Turbo model from OpenAI.
The responses generated by the model are stored as text along with their associated category.

Data Storage:

The generated synthetic data is stored in a Pandas DataFrame, which is then saved to a CSV file named synthetic_data_500_samples_with_categoriesv2.1.csv.

Output:

The script prints progress messages to indicate the generation of each sample and confirms when the data is saved to the CSV file.
