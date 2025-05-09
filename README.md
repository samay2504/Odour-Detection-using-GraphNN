# OdourGNN
#### Deep Learning based molecule odour predictor given their chemical structure, using Graph Neural Networks

<img src="figures/readme-hero.png" width="100%">

### Features
- Dataset preparation
- ML pipeline for multiclass predictions (138 classes) 
- Molecular visualization
- GNN models - GIN, GAT, GraphSAGE
- Model training & inference
- Inference Explainations
- Relative atom-bond importance visualization
- Hyperarameter tuning 
- Embedding Space visualisation

### Results 
##### Hyperparameter Tuning 
<img src="/figures/plots/hyt_fig.png" width="100%">

##### Finetuning 
<div align="center">
<img src="./figures/plots/acc.png" width="48%"> &nbsp;
<img src="/figures/plots/valloss.png" width="48%">
</div>


### Setup Instructions
__Requirements__
```
python3 = 3.11.3
pip = 24.2
```


Run the following in terminal
```bash
git https://github.com/samay2504/Odour-Detection-using-GraphNN
cd ./Odour-GNN
python3 -m venv venv 
source venv/bin/activate
pip3 install -r ./requirements.txt
```

Voila😉 Now experiment using `python3 ./main.py`


### Author
- Github - [samay2504](https://github.com/samay2504)
- Website - [Samay Mehar](https://portfolio-samay-mehars-projects.vercel.app/)
