# LMs
## About
Collection of LMs I've made. Includes N-grams. Soon to include LLMs and Transformer Models (including GPTs)

## N-gram Models
An **language model** is an ML model that predicts upcoming words. **Large language models** are models that are trained to predict words. An **n-gram** is a sequence of words: A **bigram** is a sequence of two words, a **trigram** is a sequence of three words, and so on. In the context of an n-gram model, **n-gram** also refers to the probabilistic model that predicts words based on the previous n-1 words.

For further information about N-gram models and LLMs in general, google has a nice page/course on it: https://developers.google.com/machine-learning/crash-course/llm.

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

#### Extra
Link to obtain texts: https://www.gutenberg.org/

**Disclaimer**: For the purposes of building the models, once I downloaded a text, I had to edit it, remove the licensing, and save a copy of this edited version, which I then used for the language models. I do not wish to profit off these texts in any way or distribute these texts, I just wish to use them for the purpose of training my models. It's important to read licenses when you borrow texts, even for purely education purposes such as these.

## Transformers and GPTs





