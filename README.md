# 🧠 Generative Text Model (GPT-2)

An interactive Jupyter notebook that uses the **GPT-2 language model** to generate coherent paragraphs based on user-defined prompts.

---

## 📌 Features

* Accepts user input prompts
* Generates realistic, human-like text completions
* Built using HuggingFace Transformers and GPT-2
* Clean and interactive UI with `ipywidgets`
* Notebook-based interface for easy experimentation

---

## 📦 Requirements

Make sure you have Python 3.7+ and the following packages:

```bash
pip install transformers ipywidgets notebook
```

---

## 🚀 How to Use in VS Code (or Jupyter)

1. Clone/download the project or create a new notebook file.
2. Paste the provided code into a Jupyter notebook (`.ipynb`).
3. Open the notebook in VS Code (with Jupyter extension) or Jupyter Lab.
4. Run the notebook cell.
5. Enter a topic (e.g. `"Impact of AI on education"`) and click **Generate Text**.
6. The model will return a paragraph continuation below the prompt.

---

## 🧪 Example Prompts to Try

* "The effects of climate change on agriculture"
* "Advantages of using AI in healthcare"
* "The role of cybersecurity in digital transformation"

---

## 💡 Under the Hood

* Uses `pipeline('text-generation')` from Hugging Face Transformers
* Default model is `gpt2` (117M parameters)
* Generates up to 150 tokens of completion text

---

## 📄 License

MIT License — free to use, modify, and share.

---

## 👩‍💻 Author

Harshitha YJ | Powered by OpenAI's ChatGPT
