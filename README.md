# IEformer


The code is coming soon.


# Preliminaries

This code was developed and tested with:

- Python version 3.10.4
- PyTorch version 1.12.0
- CUDA version 11.2
- tqdm version 4.64.0
- timm version 0.6.7
- scikit-learn version 1.1.2

# Experiments

## running run.py

```
python -m torch.distributed.launch --master_port 29502 --nproc_per_node=4 run.py
```
