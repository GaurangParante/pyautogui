# PyAutoGUI Practice

Small Python examples for PyAutoGUI mouse, keyboard, screenshot, and general screen automation functions.

## Create Virtual Environment

Use Python 3.11 to create the virtual environment:

```powershell
py -3.11 -m venv venv
```

## Activate Virtual Environment

In PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

In Command Prompt:

```cmd
venv\Scripts\activate.bat
```

After activation, your terminal prompt should show `(venv)`.

## Required Modules

This project uses:

- `pyautogui`
- `pyscreeze`
- `Pillow`

These modules are listed in `requirements.txt`.

## Install Requirements

After activating the virtual environment, install all required modules:

```powershell
python -m pip install -r requirements.txt
```

## Run Files

Run any script with Python:

```powershell
python general_function.py
python mouse_function.py
python keybord_function.py
python screenshot_function.py
```

## Save Installed Packages

If you install more packages later, update `requirements.txt` with:

```powershell
pip freeze > requirements.txt
```
