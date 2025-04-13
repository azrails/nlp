# NLP Projects

<p align="center">
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#content">Content</a>
</p>

<div align="center">
  <a href="/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  </a>
  <img src="https://img.shields.io/badge/python-3.8%2B-blue" alt="Python Version">
</div>

## About

This repository contains Python notebooks and mini-projects on Natural Language Processing (NLP).

Most content consists of:
- Homework assignments from HSE University courses
- Yandex training sessions
- Personal research projects exploring new NLP approaches

## Installation

1. Install [Poetry](https://python-poetry.org/) (dependency management tool):
```bash
curl -sSL https://install.python-poetry.org | python3 -
```
2. Install dependencies
```bash
poetry install
```

## Content
<!-- (TEMPLATE)
### 📁 [Project Name](/path/to/directory)
- **Description**: Brief project summary (1-2 sentences)
- **Technologies**: Main technologies/libraries used
- **Key Features**: Core functionality or implemented methods -->

### 📁 [PPO DPO aligment](./ppo-dpo/ppo_dpo.ipynb)
- **Description**: Realizing DPO aligment model pipeline from scratch, and comparision stability with standart RLHF PPO aligment.
- **Links** [Models on huggingface hub](https://huggingface.co/collections/Azrail/hw-aligment-67f985553e70a2192be195ce)
- **Technologies**: [Transformers](https://huggingface.co/docs/transformers/index) [TRL](https://huggingface.co/docs/trl/index), PyTorch
- **Key Features**: DPO from scratch, PPO with TRL
