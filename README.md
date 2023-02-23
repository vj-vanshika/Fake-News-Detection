# FAKE NEWS DETECTION
The proliferation of fake news on social media and internet is deceiving people to an extent which certainly needs to stopped.

The main objective of this project is to generate a model that can discriminate between fake and true news articles when it is trained with a certain dataset.

# WORKFLOW
1. The Dataset is acquired through Kaggle which had two different csv files namely true.csv and fake.csv.

2. Merged both of the dataset in random fashion to create a complete whole dataset by adding a new column called label which had ‘fake’ value as 1 and ‘true’ value as 0.

3. Pre-processing the dataset using Bert Tokenizer for splitting the news sentences into meaningful smaller pieces called tokens. 

4. Defining BERT Model and it's architecture by freezing some layers and fine tuning it from scratch using Deep Learning.

5. Defining the optimizer , Train and Evaluation function.

6. Designing a simple easy to use interface using Gradio Library and Predicting and calculating the performance using compute metric function.
