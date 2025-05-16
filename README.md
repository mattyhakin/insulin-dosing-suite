<p align="center">
    <img src="https://github.com/mattyhakin/insulin-dosing-suite/blob/main/insulin-dosing-header.png?raw=true" alt="Insulin Dosing Suite"/>

# Insulin Dosing Suite

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![GUI](https://img.shields.io/badge/Interface-CLI%20%7C%20Tkinter-green.svg)
![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)

**A comprehensive Python-based insulin dosing suite with CLI tools, GUI calculators, and experimental ratio input models to support diabetes management.**

---

## Features

- ✅ Command-line insulin calculator with customizable ratios
- 🧪 Experimental input model using time-of-day profiles
- 💻 Two GUI versions built with Tkinter (v1 basic, v2 improved UX)
- ⚙️ Full GitHub Actions CI/CD and test automation
- 📘 [User Guide & Documentation](./docs)

---

## Project Structure

| Module        | Description                                     |
|---------------|-------------------------------------------------|
| `cli/`        | Original command-line calculator                |
| `gui-v1/`     | First GUI version using Tkinter                 |
| `gui-v2/`     | Updated GUI with enhanced layout & accessibility |
| `experimental/` | Ratio input test models and prototypes        |
| `tests/`      | Unit tests for CLI and GUI tools                |

---

## Installation

Clone the repository:
```bash
git clone https://github.com/mattyhakin/insulin-dosing-suite.git
cd insulin-dosing-suite
pip install -r requirements.txt
```

To run the CLI tool:
```bash
python cli/main.py
```

To run the latest GUI:
```bash
python gui-v2/app.py
```

---

## License

MIT © [mattyhakin](https://github.com/mattyhakin)

---

## 📝 Notes

This repository merges and replaces the following:
- `complexinsulincalc`
- `ratioinputinsulin`
- `complexinsulincalcGUI`
- `InsulinCalcv3`

Archived versions can be found in their respective README links.
