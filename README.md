# LLMGNN

Code for our paper [Label-free Node Classification on Graphs with Large Language Models (LLMS)](https://arxiv.org/abs/2310.04668). 

## Abstract
In recent years, there have been remarkable advancements in node classification achieved by Graph Neural Networks (GNNs). However, they necessitate abundant high-quality labels to ensure promising performance. In contrast, Large Language Models (LLMs) exhibit impressive zero-shot proficiency on text-attributed graphs. Yet, they face challenges in efficiently processing structural data and suffer from high inference costs. In light of these observations, this work introduces a label-free node classification on graphs with LLMs pipeline, LLM-GNN. It amalgamates the strengths of both GNNs and LLMs while mitigating their limitations. Specifically, LLMs are leveraged to annotate a small portion of nodes and then GNNs are trained on LLMs' annotations to make predictions for the remaining large portion of nodes. The implementation of LLM-GNN faces a unique challenge: how can we actively select nodes for LLMs to annotate and consequently enhance the GNN training? How can we leverage LLMs to obtain annotations of high quality, representativeness, and diversity, thereby enhancing GNN performance with less cost? To tackle this challenge, we develop an annotation quality heuristic and leverage the confidence scores derived from LLMs to advanced node selection. Comprehensive experimental results validate the effectiveness of LLM-GNN. In particular, LLM-GNN can achieve an accuracy of 74.9% on a vast-scale dataset \products with a cost less than 1 dollar.

![Pipeline demo](./imgs/pipeline.png)


## Environment Setups



## How to use this repo and run the code

There are two main parts of our code
1. Annotators
2. GNN training

The pipeline works as follows: 



## Notes
In the beginning, I tried to maintain a good coding style 😇, but later on, due to my mental state before the deadline, I failed 😓. I'll optimize the code structure when I have more time ⏳.
