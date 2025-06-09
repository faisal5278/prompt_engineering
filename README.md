# 📘 Prompt Engineering with LangChain and Hugging Face

This project demonstrates how to use **LangChain** for prompt engineering, combined with the **Hugging Face Inference API**, to build and test various NLP tasks. It showcases how structured prompts can improve the performance and clarity of LLM outputs.

---

## 🔍 Project Overview

The notebook includes three main examples of prompt engineering:

- **Financial Advisor Prompt**  
  Uses a custom prompt to generate beginner-friendly explanations of financial concepts, such as income tax.

- **Language Translation Prompt**  
  Translates a given sentence into a target language using a simple templated prompt.

- **Few-Shot Antonym Prediction**  
  Demonstrates a few-shot learning approach by providing a model with a few examples of antonyms, then prompting it to predict the antonym of a new word.

---

## 🛠️ Technologies Used

- **LangChain** – for building structured and few-shot prompts  
- **Hugging Face Inference API** – for interacting with the `zephyr-7b-beta` LLM  
- **Python Standard Libraries** – such as `os`, `requests`

---

## 🚀 How to Run

1. **Clone the repository** and open the notebook file:  
   `prompt_engineering_langchain.ipynb`

2. **Set your Hugging Face API token** as an environment variable:

   ```python
   import os
   os.environ["HUGGINGFACEHUB_API_TOKEN"] = "your_token_here"
