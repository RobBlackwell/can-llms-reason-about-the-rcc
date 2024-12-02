# Can Large Language Models Reason about the Region Connection Calculus?

## Introduction

This repository contains benchmark questions and experimental results
from the paper:

Cohn, A.G., and Blackwell, R.E., 2024. Can Large Language Models
Reason about the Region Connection Calculus? arXiv preprint
[arXiv:2411.19589](https://arxiv.org/abs/2411.19589).

## Data

We have encrypted the data using a simple password ("123") to avoid
our questions and answers becoming LLM training data.

We prepared the data like this:

``` bash
tar -czvf data.tar.gz data
gpg --symmetric --cipher-algo AES256 data.tar.gz
```

To decrypt and uncompress the data, please use the following commands, providing the password "123" when prompted.

``` bash
gpg --decrypt -o data.tar.gz data.tar.gz.gpg
tar -zxvf data.tar.gz
```
