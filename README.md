# QuestionAnswering_Cosmos

This project tries to fine tune a BERT base uncase model from Hugging Face to perform Question Answering for the CosmosQA dataset. 

To run this program the following steps should be performed:

1) Open the CosmosQA python notebook in any desired location. I suggest changing the runtype to a powerful GPU since fine tuning a BERT model can be computationally intensive.
2) Run all the cells
3) See the final F1 score results.

Note: The Cosmos dataset is taken from HuggingFace link: https://huggingface.co/datasets/cosmos_qa
This dataset does not contain any true testing data, since all the labels in the test data are -1. Thus the final F1 score is based off the Validation set.
