# Delphi

Official implementation of **Delphi: Calibrated Uncertainty for Retrieval-Augmented Generation**.

## Installation

```bash
pip install -r requirements.txt
```

## Repository structure

```
src/calibrate.py
src/retriever.py
src/generator.py
train.py
eval.py
requirements.txt
```

## Training

Run `python train.py --config configs/default.yaml` to reproduce the main results.
Checkpoints and logs are written to `runs/`.

## Evaluation

Run `python eval.py --checkpoint runs/latest` to reproduce the benchmark tables.

## Citation

```bibtex
@inproceedings{misc,
  title = {Delphi: Calibrated Uncertainty for Retrieval-Augmented Generation},
  booktitle = {Proceedings of the corresponding venue},
  year = {2025}
}
```
