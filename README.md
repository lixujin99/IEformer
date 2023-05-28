# EIformer


# Preliminaries

This code was developed and tested with:

- Python version 3.10.4
- PyTorch version 1.12.0
- CUDA version 11.2
- The conda environment defined in ```environment.yml```

The conda environment defined in environment.yml
```
conda env create -f environment.yml  # create conda env
```


# Experiments

## running run.py

```
python -m torch.distributed.launch --master_port 29502 --nproc_per_node=4 run.py
```
