# Detecting Natural Language Biases with Prompt-based Learning

## Members:

- Md Abdul Aowal
- Maliha T Islam
- Priyanka M Mammen
- Sandesh Shetty

This project aims to identify the inherent bias of certain pre-trained models. Given masked inputs aimed to generate biased outputs, we generate the first and second most likely outputs from our models.
We then try to identify this bias both by human evaluation and using the models themselves on a cloze-style question. 

## Running:

The code is present in `bias-detection.ipynb`. It requires these three files `inputs.tsv`, `t5_preds1.txt` and `t5_preds2.txt`.

The evaluated (model/human) outputs is present under the `baselines_with_annotated.csv` file.
