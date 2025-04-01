# Exploring-the-Effects-of-Symbol-Tuning-on-In-Context-Learning
The codebase for the master's thesis work: "Exploring the Effects of Symbol Tuning on In-Context Learning."

# Reproducing and Extending the Study

This work aims to reproduce and extend the study: [arXiv:2305.08298](https://arxiv.org/abs/2305.08298).

## Prerequisites

Before starting with the code, ensure that you have completed the following steps:

1. **WINO Dataset**
   - You have a folder named `WINO dataset` containing the datasets.
   - Download the datasets from: [Winogrande Dataset](https://winogrande.allenai.org/).

2. **Generate Symbols Folder**
   - You have a folder named `generate_symbols`.
   - Inside, create an `__init__.py` file.
   - Download the necessary files from: [Symbol Tuning Repository](https://github.com/JerryWeiAI/symbol-tuning).

3. **Hugging Face Account**
   - You have created an account on [Hugging Face](https://huggingface.co/).

4. **Hugging Face Access Token**
   - You have created an access token with **read permissions**.
   - For more details, visit: [Hugging Face Security Tokens](https://huggingface.co/docs/hub/security-tokens).

5. **Model Access on Hugging Face**
   - You have requested access for the following models from their Hugging Face card pages:
     - [Llama 3.1-8B Instruction-Tuned](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)
     - [Llama 3.2-3B Instruction-Tuned](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct)
     - [Gemma 7B Instruction-Tuned](https://huggingface.co/google/gemma-7b-it)

6. **Package Installation**
   - You have installed the necessary packages according to the `requirements.txt` file.

Once all these steps are completed, you are ready to proceed with the code!
