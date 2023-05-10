## STMBR
Implementation for our paper **Sinkhorn Transformer for Multi-Behaviour Recommendation**.

## Requirements
The code is built on Pytorch and the [RecBole](https://github.com/RUCAIBox/RecBole) library. Use following command to install the requeiremnts:

`pip install -r requirements.txt`


## Datasets

##### Unzip the datasets and move them to the *./dataset/* directory

## Run STMBR

`python runSTMBR.py --model=[STMBR] --dataset=[tmall_beh] --gpu_id=[0] --batch_size=[2048]`, where [value] is the default value.

## Tips
- Note that we modified the evaluation sampling setting in `recbole/sampler/sampler.py` to make it static.
- The model code is at `recbole/model/sequential_recommender/stmbr.py`.
- Feel free to explore other RecBole library baseline models to compare the performances.
