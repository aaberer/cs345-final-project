# Developing Guidelines

## Quick Setup

### 1. Install dependencies

```bash
pip install -r dependencies.txt
```

### 2. Verify installation

```bash
python -c "import sklearn; import pandas; import matplotlib; print('All dependencies installed!')"
```

### 3. Run the notebook

```bash
jupyter notebook main.ipynb
```

## Data Setup

Ensure your datasets are placed in the `data/` directory with the structure shown above. Each dataset should contain:

- `corpus.tsv`: Main dataset with columns `source_url`, `source_url_normalized`, `ref`, `fact`, `bias`
- `splits.json`: Train/dev/test split indices
- `features/`: Directory containing pre-computed feature JSON files
