# Pointerformer

We provide code, data and trained models. 

## Requirements

```
conda create -n python=3.7
pip install -r requirements.txt
```

## Trained Model and Dataset

You can download our trained models and datasets from [here](https://drive.google.com/file/d/1Sx5hkXTzYSZ98Iqf1UWJdQfVhCbJGgpz/view?usp=sharing "trained_model_and_data.zip"), then unzip the files to the root directory of this project.

## Train

train a model on TSP100.

`python train.py graph_size=100 group_size=100`

## Evaluate

eval on tsp_random

`python eval.py val_data_path=./data/tsp100_test_concorde.txt load_checkpoint_path=./result_ckpt/model100.ckpt`
