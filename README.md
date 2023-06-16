# Fine-tuning GPT-2 for multi-task dialogue summarization 

This repository contains code for multi-task dialogue summarization: extractive + abstractive. <br>
Base model: [GPT-2 small](https://huggingface.co/gpt2) <br>
Dataset: [AMI](https://groups.inf.ed.ac.uk/ami/corpus/)

# Repo structure

### root folder
The main folder contains **3** following Jupyter notebooks:

 - Baselines.ipynb. Code for baselines
 - Fine-tuning GPT-2.ipynb. Code for the main experiment: fine-tuning GPT-2 model for extractive + abstractive dialogue summarization
 - Generation.ipynb. Overview of used generating techniques 

### data
The data folder contains train and test sets used for experiments. The data is taken from AMI dataset. 


### results

The results folder contains rouge metrics for all created models (rouge_scores folder) and predictions from main models for test set (generation_examples).

This repository contains code and results for the masters thesis [Multitask Dialog Summarization With Transfer-Learning](https://drive.google.com/file/d/1OCnZc4H6ewOMyAToacg8lO1c4Nd-Rbmk/view?usp=sharing) (written in Russian)
