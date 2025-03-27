# Medical-Query-Response-Chatbot

# Steps to run:

Clone the repository
```bash
git clone https://github.com/Mozeel-V/Medical-Query-Response-Chatbot.git
```

## STEP 1: Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

## STEP 2: Activate the environment

```bash
conda activate medibot
```

## STEP 3: Install the requirements

```bash
pip install -r requirements.txt
```

## STEP 4: Create the vector database

```bash
python store_index.py
```

## STEP 5: Run the app on your localhost

```bash
python app.py
```