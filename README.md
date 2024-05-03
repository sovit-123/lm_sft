# README

Various LMs/LLMs below 3B parameters (for now) trained using SFT (Supervised Fine Tuning) for several downstream tasks like:

* Following instructions (the general instruction fine tuning)
* Question Answering
* Summarization
* Headline generation
* Sentiment analysis
* Text classification
* Language translation
* Code generation
* And more coming...

## Setup

* Create a Conda environment:

```
conda create -n env_name python=3.11
```

* Installing `packaging`:

```
pip install packaging
```

* Install PyTorch (you can install the version of your choice from [here](https://pytorch.org/get-started/locally/))

```
conda install pytorch==2.2.0 pytorch-cuda=12.1 -c pytorch -c nvidia
```

* Install rest of the requirements:

```
pip install -r requirements.txt
```

