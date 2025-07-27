Overview
Fine-tuned CodeT5-small model to generate descriptive comments for Python code snippets using the MBPP dataset.

Dataset
MBPP dataset with ~1000 samples of Python code and corresponding task descriptions (used as comments).

Model
Pretrained Salesforce/codet5-small fine-tuned for 3 epochs.

Results
BLEU score on evaluation set (38 samples): 31.56

Qualitative results show the model generates meaningful and relevant comments, though some comments are generic or imprecise.

Challenges
Limited dataset size affects generalization.

Some generated comments slightly differ in phrasing from ground truth but capture intent.
