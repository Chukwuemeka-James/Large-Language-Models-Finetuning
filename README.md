# Large Language Model Fine-Tuning

## Overview
This repository is dedicated to the **Colab ML Enginnering Community** and leaners all over the world, it contains a structured workflow for fine-tuning Large Language Models (LLMs). The notebooks guide you through the key steps of curating data, evaluating frontier models, fine-tuning OpenAI models, fine-tuning opensource models from huggingface, and leveraging quantization techniques.

## Contents

### Jupyter Notebooks
1. **01_Data Curation for Large Language Models.ipynb**  
   - Initial steps in preparing data for LLM fine-tuning.

2. **02_Data Curation for Large Language Models.ipynb**  
   - Further refinements and optimizations in data curation.

3. **03_Evaluating Frontier Models.ipynb**  
   - Benchmarking and assessing performance of pre-trained models.

4. **04_Fine-Tuning an OpenAI Model.ipynb**  
   - Steps to fine-tune an OpenAI model on custom datasets.

5. **05_Quantization Techniques.ipynb**  
   - Methods to reduce model size and optimize inference.

6. **06_Tokenization and Base Model Evaluation.ipynb**  
   - Understanding tokenization processes and evaluating base models.

7. **07_QLORA Finetuning and Model Training.ipynb**  
   - Implementing QLoRA (Quantized Low-Rank Adaptation) for efficient fine-tuning.

8. **08_Evaluating Fine-Tuned Model.ipynb**  
   - Assessing model performance after fine-tuning.

### Utils Folder
The `utils` folder contains helper scripts to support the fine-tuning pipeline:

- **items.py**  
  - Defines an `Item` class for data cleaning and tokenization.
  - Implements methods to prepare dataset samples for training.

- **loaders.py**  
  - Loads and processes datasets efficiently using multiprocessing.
  - Extracts relevant product metadata for fine-tuning.

- **testing.py**  
  - Implements evaluation functions for assessing model accuracy.
  - Provides visualization tools for error analysis.

## Acknowledgments
This repository was inspired by and incorporates ideas from the excellent work done in:
- [Ed-Donner LLM Engineering Repository](https://github.com/ed-donner/llm_engineering)

