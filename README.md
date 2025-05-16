# MultiLang-Translator-Neural-Machine-Translation-with-HuggingFace-Transformers

# 🚀 Installation
**Get started by installing the required Python libraries:**

pip install transformers
pip install torch

💡 Make sure you have Python 3.6+ and an active internet connection to download the pretrained models.

# **⚙️ How to Use**
Use the translate() function by specifying the input text, source language, and target language codes (e.g., 'en', 'de', 'fr').

translated = translate("My name is Bilal", "en", "de")
print("Translated:", translated)

# **🧠 Behind the Scenes**
This translator leverages:

MarianMTModel and MarianTokenizer from Hugging Face

Pretrained models by Helsinki-NLP

Tokenization → Encoding → Translation → Decoding pipeline

PyTorch for efficient inference

**🌍 Supported Language Pairs**
Source	Target	Model ID
English (en)	German (de)	Helsinki-NLP/opus-mt-en-de
English (en)	French (fr)	Helsinki-NLP/opus-mt-en-fr
German (de)	English (en)	Helsinki-NLP/opus-mt-de-en
French (fr)	English (en)	Helsinki-NLP/opus-mt-fr-en

📁 Project Structure


├── translate.py            # Main translation logic
├── README.md               # Project documentation
└── requirements.txt        # (Optional) Dependency list

**🪪 License**
Feel free to use and modify it as needed.

**🤝 Contribute**
Feel free to fork this repo, suggest features, or fix issues through pull requests! Contributions are welcome.
