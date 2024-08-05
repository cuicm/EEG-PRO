Preprocessed data can be downloaded from https://zenodo.org/records/13219018

Pre-training: 

```
python Pretrain.py
```

Prompt tuning:

```
python tuning_.py --dataset PROCESSED/SHL.pth --tuning eeg-pro --model_path saved_models/encoder.pth --lr_decay True --batch_size 64 --num_epochs 500 
```
