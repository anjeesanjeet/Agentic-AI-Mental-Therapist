# Agentic-AI-Mental-Therapist

# How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/anjeesanjeet/Agentic-AI-Mental-Therapist.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `config.py` file in the backend directory and add your Twilio  & openai credentials as follows:

```ini
TWILIO_ACCOUNT_SID = ""
TWILIO_AUTH_TOKEN = ""
TWILIO_FROM_NUMBER = ""  # your Twilio number
EMERGENCY_CONTACT = ""  # or your local emergency number
OPENAI_API_KEY=""
```


```bash
# run the following command to start the backend engine
python backend/main.py
```

```bash
# Finally run the following command in another terminal
streamlit run frontend.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- FastAPI
- Ollama
- Twilio
