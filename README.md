README.md – quickstart, dataset links, and config usage

requirements.txt – exact dependencies


configs/ – YAML configs for Kvasir and CVC-ClinicDB

hssam/

model.py – full HSSAM-Net (HSSAM, PRA, MaxDP/MaxDUP-based encoder/decoder)

dataset.py – robust dataset loader for images/ + masks/

metrics.py – Dice, IoU, and extended metrics (TPR/TNR/PPV/NPV/FPR/FNR/FDR/FOR)

train.py – mixed-precision training with warmup

evaluate.py – evaluation + extended metrics reporting
