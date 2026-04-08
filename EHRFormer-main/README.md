# EHRFormer
Official implementation for paper "EHRFormer: A Next-Visit Diagnosis Prediction Model Using Electronic Health Records via Temporal Graph Transformer"

## Requirements

Requirements and recommended versions:

Python (3.10.13)

pytorch (1.12.1)

torch-geometric (2.3.1)

Pyhealth (1.1.4)

## Data Processing

For MIMIC-III and MIMIC-IV: refer to https://pyhealth.readthedocs.io/en/latest/api/datasets.html; 

For CCAE: Run process_ccae.ipynb in the data folder.


## Training & Evaluation

To train the model and baselines in the paper, run this command:

```
python train.py --model <EHRFormer/Transformer/...> --dataset <mimic3/mimic4/...>
```

## Notice
Due to the intellectual property protection agreement of the author's institution, the model weights are not made public.