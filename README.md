# PocketLLM
Ultimate Compression for Large Language Models via Meta Networks

## Acess
paper: https://arxiv.org/pdf/2511.17637

## Environment
```
pip install -r requirements
```
## Preprocess
```
python save_npy.py
```
## Training
```
sh train_llama.sh
```
## Reconstruction
```
sh rec.sh
```
## Fine-tuning (optional)
use standard lora finetuning with redpajama or alpaca.
parameters:r=32, alpha=64, bs=16, epoch=3, lr=1e-4

## Test
lm-evaluation-harness for acc.
wikitext-2 / C4 for ppl .

## Citation
To do
