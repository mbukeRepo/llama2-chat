# Fine-tuning LLAMA-2 to code OPL

In this project I fine-tuned llama-2-7b base model to code a fictional programming language called OPL.

## Pre-requisites

- Python interpreter
- Conda  package manager 
- Basics of deep learning

## Setting up

- Install conda packages:
```
conda install --yes --file requirements.txt
```
- Install pip packages:
```
pip install -r requirements.pip.txt
```

- Load jupyter notebook:
```
jupyter notebook --no-browser --port=8888
```
- During the finetuning of llama-2 I used a remote server with a gpu, to connect with remote jupyter notebook
you can use ssh tunneling. 

```
ssh -N -L localhost:8000:localhost:8888 your_username@remote_server_address
```

## Citations

```
@Video{fine_tune_llama2_to_code,
  author = {Chris_Hay},
  title = {{how to fine tune llama2 to code in a new programming language}},
  url = {https://www.youtube.com/watch?v=5wGD92ktQL4},
  year = {2023}
}
```

```
@article{FineTune_Your_Own_Llama_2,
  author = {Maxime Labonne},
  month = {7},
  number = {25},
  pages = {1},
  title = {{Fine-Tune Your Own Llama 2 Model in a Colab Notebook}},
  volume = {1},
  year = {2023}
}
```
