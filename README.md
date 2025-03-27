# Medical-Query-Response-Chatbot

# Steps to run:

## STEP 1: Clone the repository

```bash
git clone https://github.com/Mozeel-V/Medical-Query-Response-Chatbot.git
```

## STEP 2: Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

## STEP 3: Activate the environment

```bash
conda activate medibot
```

## STEP 4: Install the requirements

```bash
pip install -r requirements.txt
```

## STEP 5: Create the vector database

```bash
python store_index.py
```

## STEP 6: Run the app on your localhost

```bash
python app.py
```