# Source-Code-Analysis-GenAI

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/sxg2520/Source-Code-Analysis-GenAI.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n sca python=3.8 -y
```

```bash
conda activate sca
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your OPENAI_API_KEY credentials as follows:
Ensure to remove API Key from research notebook before committing changes
```ini
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
python app.py
```

### Techstack Used:

- Python
- LangChain
- Flask
- OpenAI
- GPT 3.5
- ChromaDB

