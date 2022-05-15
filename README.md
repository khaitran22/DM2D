# DM2T
This repository contains the source code and dataset for the paper: ***"Improving Traffic Load Prediction with Multi-modality: A Case Study of Brisbane"***

## Dataset
Datasets used for developing models are provided under `/dataset`. 
This dataset is the traffic load of the Coronation Drive in Brisbane, Australia. For information about the meaning of the column, please refer to [this website](https://www.data.brisbane.qld.gov.au/data/dataset/traffic-data-at-intersection-api).

The data provided is pre-processed. Please contact author if you need the raw data.

You can download raw data from [this website](https://www.data.brisbane.qld.gov.au/data/dataset/traffic-data-at-intersection-api) by using API. Note the data is in real-time.

## Files
1. `main-models-training.ipynb`: main models development (CNN, RNN and LSTM)
2. `sentiment-classification-for-tweets-all-brisbane.ipynb`: Sentiment classification for Brisbane tweets
3. `training-sentiment-analysis-model.ipynb`: Training sentiment classifier
4. `visualizing-main-models.ipynb`: Visualizing the prediction from 3 main models

## Pre-trained model
We also provide pre-trained model used in our paper under folder `/trained models`.

## Environments detail
CUDA Version: 10.2  

Nvidia GeForce RTX 2080 GPU

Python 3.8.10

Tensorflow 2.4.0

## Citation
	@inproceedings{tran2022improving,
        title={Improving Traffic Load Prediction with Multi-modality},
        author={Tran, Khai Phan and Chen, Weitong and Xu, Miao},
        booktitle={Australasian Joint Conference on Artificial Intelligence},
        pages={254--266},
        year={2022},
        organization={Springer}
      }