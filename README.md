# askmydocs

Tiny retrieval pipeline: TF-IDF chunks + pluggable LLM step

## Usage

```bash
python rag.py ./notes "how do I rotate logs?"
```

## Getting started

```bash
pip install -r requirements.txt
```

## What it does

- Prints sources with scores for transparency
- Swap in any LLM for the answer step
- TF-IDF retrieval: zero external services needed
- Chunk markdown with overlap, keep source paths

## Project structure

```text
├── data/
│   └── sample.md
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── rag.py
└── requirements.txt
```

## Notes

- mostly stable, edge cases remain
