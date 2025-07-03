Author: Alexander Davis
Date: 08/01/2024

Purpose: The purpose of this project is to ingest global research data and discover insights through topic modeling.


Scripts:
	- data_load.pynb: This notebook is for data ingestion using the OpenAlex API and data preprocessing to prepare the text for the topic model.
	- modeling.pynb: This notebook is for building a topic modeling and tuning hyperparameters to optimize the model. This script outputs interactive files to explore the topics created by the model.
	- bert_topic_model.pynb: This notebook is for building a topic model utlizing LLMs and various models.


Data:
	- preprocessed_data.pkl: This is an output of data_load.pynb. It is the preprocessed text data that feeds into the model in modeling.pynb.

Outputs:
	- lda_draft.html: An interactive visualization of the draft topic model.
	- lda_final.html: An interactive visualization of the final topic model.