# Diffusion-Jump-GNNs
Diffusion-Jump GNNs: Homophiliation via Learnable Metric Filters
## Dependencies

Conda environment
```
conda create --name <env> --file requirements.txt
```

or

```
conda env create -f environment_experiments.yml
conda activate DiffWire
```
## Code organization
## Run experiments
```python
python train.py --dataset REDDIT-BINARY --model CTNet --cuda cuda:0
python train.py --dataset REDDIT-BINARY --model GAPNet --derivative laplacian --cuda cuda:0
python train.py --dataset REDDIT-BINARY --model GAPNet --derivative normalizeed --cuda cuda:0
```
