# CustomSum
[![python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/downloads/release/python-3112/)

Create custom summarization of extensive documents through fast parallelized predictions, utilizing [GPT-3.5](https://platform.openai.com/docs/models/gpt-3-5) and [GPT-4](https://platform.openai.com/docs/models/gpt-4) APIs provided by [OpenAI](https://openai.com/).

## Overview

Summarize text from different sources.
- 📄 Summarize document (.pdf, .docx, .txt, .md).
- 🎥 Summarize YouTube video with subtitles.
- 🚀 Facilitates parallel processing of chunks, enabling ultra-fast generation speeds.
- 🧠 Supports GPT-3.5 and GPT-4.

![Screenshot from 2023-10-02 20-44-34](https://github.com/sokolheavy/CustomSum/assets/36013697/94c9a5bd-d241-4e65-9097-37d8160ed6e8)

## Instructions

- Install the requirements

```bash
pip install -r requirements.txt
```

- Get a GPT API key from [OpenAI](https://platform.openai.com/account/api-keys) if you don't have one already.

- Paste your API key in a file called `.env` in the root directory of the project.

```bash
OPENAI_API_KEY=<your key here>
```

### 💻 Running Locally
- Make sure you have **[python 3.11](https://www.python.org/downloads)** | [python installation tutorial (YouTube)](https://youtu.be/HBxCHonP6Ro?t=105)
1. Clone the repository
```bash
git clone https://github.com/sokolheavy/CustomSum
```
2. Execute `streamlit run src/CustomSum.py
`
