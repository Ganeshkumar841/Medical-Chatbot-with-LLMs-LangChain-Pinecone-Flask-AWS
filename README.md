# Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS
# How to run?

clone the repository

```bash
git clonehttps://github.com/Ganeshkumar841/Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
```

# STEP - 1 create a conda environment after opening the repository

# Anaconda ships with a script that initializes conda for shells.

# Open Git Bash.

# Run this command (assuming you installed in C:\Users\ganes\anaconda3):

# source ~/anaconda3/etc/profile.d/conda.sh

# Accept the Tos terms in the anaconda prompt
# with these two run one after other 
# conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r
# conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/msys2

```bash
conda create -n medibot python=3.13.5 -y
```

```bash
conda activate medibot
```
# STEP - 2 install the requirements
```bash 
pip install -r requirements.txt
```