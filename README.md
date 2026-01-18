# BackPropagationNotebook

Experimenting with backpropagation in a single Jupyter notebook. :contentReference[oaicite:1]{index=1}

## What’s inside
- `micro_gradient.ipynb`: builds a tiny scalar autograd engine and uses it to run backprop on simple expressions. :contentReference[oaicite:2]{index=2}

## How to run
1. Clone the repo
2. Create a venv (optional, but recommended)
3. Install Jupyter
4. Open the notebook

```bash
git clone https://github.com/lmfor/BackPropagationNotebook.git
cd BackPropagationNotebook
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install jupyter
jupyter lab
