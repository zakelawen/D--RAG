

## 🖼️ Framework

<p align="center">
  <img src="figure/D²-RAG.svg" alt="D²-RAG Framework" width="90%">
</p>



## 📋 Content
1. [⚙️ Installation](#installation)
2. [🚀 Quick Start](#quick-start)
3. [📊 Baselines](#baselines)


## ⚙️ Installation
You can create a conda environment by running the command below.

```bash
conda env create -f environment.yml
```

## 🚀 Quick start
We provide [example data](example_data.jsonl). You can get our final results by by running the command below.

```bash
python example.py
```

📝 Your input file should be a `jsonl`.

[example.ipynb](example.ipynb) contains the complete implementation of our pipeline.

```bash
run example.ipynb
```

we use Qwen3-Embedding-4B as our embedding model. 

📚Medical textbook data coming soon.

[get_context_for_each_query_V2.py](get_context_for_each_query_V2.py) — Retrieves relevant documents for each query, powered by [LlamaIndex](https://www.llamaindex.ai/).

```bash
python get_context_for_each_query_V2.py
```

## 📊 Baselines

Implementation code for a subset of baseline methods.

Retrieval-Augmented Generation baseline.

```bash
run RAG.ipynb
```

Context-Aware Decoding (CAD) baseline.

```bash
run cad.ipynb
```

## Citation

```bash
@inproceedings{Zhang2026d-rag,
    author    = {Jinshuo Zhang, Xiaoding Zhou, Weiyu Zhang, Guoqiang Chen, Ying Lian, Xiaoyang Meng, Yonghe Chen, Hongjiao Guan, Jiasheng Si and Wenpeng Lu},
    title     = {{D}$^2$-{RAG}: Dual-Decision Retrieval-Augmented Generation via Multi-Dimensional Uncertainty and Utility-Aware Decoding},
    booktitle = {Findings of the Association for Computational Linguistics: ACL 2026},
    year      = {2026}
}

```








