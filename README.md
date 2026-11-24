# Question Answering Distilbert Squad

Extractive question answering with BERT and DistilBERT on SQuAD and Quoref.

## What it does

Three notebooks on extractive QA: using a pretrained BERT pipeline on SQuAD, fine-tuning DistilBERT on SQuAD with EM/F1 evaluation and error analysis, and fine-tuning DistilBERT on Quoref.

## Files

- `question_answering_bert_squad.ipynb`
- `squad_distilbert_finetune.ipynb`
- `quoref_distilbert_finetune.ipynb`

## Tools

Hugging Face Transformers and Datasets, PyTorch, evaluate, numpy, pandas

## Dataset

[SQuAD](https://huggingface.co/datasets/rajpurkar/squad) and [Quoref](https://huggingface.co/datasets/allenai/quoref) from Hugging Face

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Quoref DistilBERT (small subsample run): exact match 15.6, F1 24.85.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
