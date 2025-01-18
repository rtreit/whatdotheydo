# whatdotheydo
Ever wonder what someone in your org actually works on? 

This project tries to answer that. 

First up: Azure DevOps history. 

Given an ADO org and Project, analyze commit history to summarize a user's activity. 

# Getting started
```powershell
python -m venv .env
.\.venv\\Scripts\Activate.ps1
pip install -r requirements.txt
```

Create a .env file with:
```text
ADO_PAT=<your ADO PAT goes here>
ADO_ORG=<org name>
ADO_PROJECT=<project name>
```

Fire up VS Code or start jupyter notebook, tweak the settings, and run.
