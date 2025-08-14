### Day 4 – Media Demos

This project contains a Jupyter notebook and sample media assets for exercises and demos.

## Contents
- `demo1.ipynb`: main notebook for the day's exercises
- `photos/`: sample images
- `videos/`: sample videos

## Project structure
```
.
├─ demo1.ipynb
├─ photos/
│  ├─ dog-img1.jpg
│  └─ mix-animal-human.jpg
└─ videos/
   ├─ mountain.mp4
   └─ ppy.mp4
```

## Requirements
- Python 3.9+
- pip

## Setup
```bash
# From the project root
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\\Scripts\\activate
pip install --upgrade pip
pip install jupyter
```

## Run the notebook
```bash
jupyter notebook demo1.ipynb
```

## Notes
- Keep the `photos/` and `videos/` folders in place so relative paths in the notebook resolve correctly.
- If additional Python packages are needed, install them in the same virtual environment with `pip install <package>`.

