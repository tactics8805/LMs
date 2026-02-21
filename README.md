# LLMs
Collection of LLMs I've made

## N-gram Models
An **language model** is an ML model that predicts upcoming words. **Large language models** are models that are trained to predict words. An **n-gram** is a sequence of words: A **bigram** is a sequence of two words, a **trigram** is a sequence of three words, and so on. In the context of an n-gram model, **n-gram** also refers to the probabilistic model that predicts words based on the previous n-1 words.

### PyTorch virtual environment and notes

Activate the venv (PowerShell):
& "pytorch_env\Scripts\Activate.ps1"

Activate (cmd):
python -m venv pytorch_env
pytorch_env\Scripts\activate.bat

Install requirements:
python -m pip install -r requirements.txt

Run the Jupyter notebook (in VS Code or Jupyter):
- Open the notebook and ensure the kernel uses the `pytorch_env` interpreter.
- Run the "PyTorch device check" cell to verify CUDA and basic tensor ops.

### Bigram Model Project
#### Overview
Predicts a sequence of 2 words, using character-level tokenizers. I use "Alice's Adventures in Wonderland" as my text/context for the model.
#### Dependencies
Project Python dependencies:
- torch==2.10.0

Link to obtain texts: https://www.gutenberg.org/


