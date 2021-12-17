# Detecting Natural Language Biases with Prompt-based Learning

## Members:

- Md Abdul Aowal
- Maliha T Islam
- Priyanka M Mammen
- Sandesh Shetty

We explore the newly-emerging field of prompt engineering and apply it to the downstream task of detecting LM biases. More concretely, we explore how to design prompts that can indicate 4 different types of biases: (1) gender, (2) race, (3) sexual orientation, and (4) religion based. Within our project, we experiment with different manually crafted prompts that can draw out the subtle biases that may be present in the language model. We apply these prompts to multiple variations of popular and well-recognized models: BERT, RoBERTa, and T5 to evaluate their biases. We provide a comparative analysis of these models and assess them using a two-fold method: use human judgement to decide whether model predictions are biased, and utilize model-level judgement (through further prompts) to understand if a model can self-diagnose the biasness of its own predictions.

## Running:

The code is present in `bias-detection.ipynb`. It requires these three files `inputs.tsv`, `t5_preds1.txt` and `t5_preds2.txt`.

The evaluated (model/human) outputs is present under the `baselines_with_annotated.csv` file.
