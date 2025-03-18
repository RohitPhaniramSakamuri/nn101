Get Started: (On Windows)

1. I use powershell. To allow venv usage from powershell, I do: "Set-ExecutionPolicy -Scope Process -ExecutionPolicy Unrestricted"
2. To create venv called "env", do: "python -m venv env"
3. To activate the venv, do: "env/Scripts/Activate.ps1"
4. To get your python modules updated, when starting a new session of work/after pulling, do: "pip -r requirements.txt".
5. Before pushing, remember to do "pip freeze > requirements.txt"