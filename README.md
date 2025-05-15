# 🌐 Basic Translator Using API

This project is a simple language translator built using Python and the `deep_translator` library. It translates input text from a source language to a target language using an API (Google Translator in this case).

## 📌 Features

- Translate any text from one language to another
- Supports a wide variety of languages
- Simple and interactive input/output flow
- Easily extendable for use in other applications

## 🛠️ Tech Stack

- **Python 3**
- **Jupyter Notebook**
- **deep-translator library**

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/basic-translator-using-api.git
cd basic-translator-using-api
````

2. **Install required packages**

```bash
pip install deep-translator
```

3. **Run the notebook**

You can run the Jupyter notebook using:

```bash
jupyter notebook Basic_Translator_Using_API.ipynb
```

## 🚀 Usage

1. Run all cells in the notebook.
2. You'll be prompted to:

   * Enter the sentence you want to translate
   * Specify the source language (e.g., `en` for English)
   * Specify the target language (e.g., `fr` for French)
3. The translated sentence will be printed in the output.

## 📚 Example

```python
Enter a sentence: Hello, how are you?
Enter the source language: en
Enter the target language: es
```

**Output:**

```
Hola, ¿cómo estás?
```

## 📖 Supported Languages

The `deep-translator` library supports many languages. You can refer to [deep-translator documentation](https://pypi.org/project/deep-translator/) or list supported languages in the notebook via:

```python
from deep_translator import GoogleTranslator
print(GoogleTranslator.get_supported_languages(as_dict=True))
```

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to contribute or suggest improvements!
```
Would you like me to save this as a `README.md` file and include it in your repo or download?
```
