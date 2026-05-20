# KAN-ER
Code for "KAN-ER: Kolmogorov-Arnold Networks-based Entity Resolution in Data Lakes" DaWaK 2026
Keywords: Data Lakes, Data Quality, Entity Resolution, Entity Matching, Machine Learning.
# KAN-ER: Entity Resolution with Kolmogorov-Arnold Networks

## Requirements
```
pip install -r requirements.txt
```

## Datasets
Download the benchmarks from the [Magellan repository](https://github.com/anhaidgroup/py_entitymatching).
Place each dataset folder under `datasets/` (e.g. `datasets/iTunes/`).

## Running an experiment
```
python experiments/itunes_amazon.py
```
Set the `BASE_PATH` variable at the top of each script to your local dataset path.

## Results
Reproduces Table 2 from the paper. Expected F1 scores: ...

## Citation
