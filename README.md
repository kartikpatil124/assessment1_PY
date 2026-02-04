# Interactive Personal Data Collector

This repository contains `assessment1.ipynb`, a small interactive Jupyter Notebook that collects basic personal information (name, age, height, favorite number and birth date) and computes the user's age from their birth date.

## Description

`assessment1.ipynb` is a learning/exercise notebook intended to demonstrate basic Python input handling, date arithmetic using the `datetime` module, and simple printing/formatting of collected values. It prompts the user for several fields and prints the collected information along with an age calculation.

## Features
- Interactive prompts for name, age, height, favorite number, and birth date
- Age calculation using the `datetime` module with birthday adjustment
- Prints object ids for demonstration/learning purposes

## Requirements
- Python 3.8 or newer
- Jupyter Notebook or JupyterLab to run the notebook interactively

The notebook uses only the Python standard library (`datetime`), so no external packages are required to run the notebook as-is.

## Usage

Open and run the notebook interactively (recommended):

```bash
jupyter notebook assessment1.ipynb
```

Or run via Jupyter Lab:

```bash
jupyter lab
```

If you need a script version, convert the notebook to a Python script (note: `input()` calls will still require interactive input):

```bash
python -m nbconvert --to script assessment1.ipynb
python assessment1.py
```

## Privacy & GitHub Upload Guidance
- The notebook prompts for personal data. Do not commit or push outputs containing real personal information to a public repository.
- Before uploading to GitHub, clear notebook outputs or use `.gitignore` to avoid tracking exported files that contain personal data.

To clear outputs in Jupyter: `Kernel -> Restart & Clear Output` or use the Notebook editor's "Clear All Outputs" command.

## Notes
- The age calculation accounts for whether the birthday has already occurred in the current year.
- This notebook is intended for educational/demo purposes only.

## Contributing
Feel free to open issues or PRs to improve prompts, add validation, or convert this into a GUI/web form for safer data handling.

## License
This repository is provided under the MIT License. See `LICENSE` if included.
