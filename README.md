# `pyquist`

New Python library for CMU 15-322 Intro to Computer Music. WIP.

Principles:

- Simple
- Minimal dependencies
- Accessible implementations
- Well-documented core functionality

## Installation

### Mac OS X

Install Python3 and virtualenv

```sh
git clone git@github.com:gclef-cmu/pyquist.git
cd pyquist
python3 -m venv venv
source venv/bin/activate
pip install -e .
pip install numpy sounddevice jupyter ipykernel ipywidgets
python -m ipykernel install --user --name=pyquist --display-name "Pyquist"
cd examples
jupyter notebook
```

## Development installation

```sh
brew install python@3.10
python3.10 -m venv venv3
source venv/bin/activate
pip install pre-commit
pre-commit install
```

## Acknowledgements

Inspired by:

- Tone.js
- JUCE
- Nyquist
