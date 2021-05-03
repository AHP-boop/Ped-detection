# MGAN Ped Occlusion


Installation:

git clone https://github.com/AHP-boop/Ped-detection.git


Dataset: Caltech and Cityscape

## Testing

```
python tools/test.py city_cfgs/mgan_50_65.py models/50_65.pth --out result/50_65.pkl
```
## Eval

```
python eval/eval_demo.py
```
