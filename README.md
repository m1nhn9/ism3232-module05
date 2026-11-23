# Module 5: Functions and Debugging

Weeks 7–8 cover business-rule functions, imports, pytest, and debugging.

- `business_rules.py` and `main.py`: the four Week 7 business rules and demo.
- `week8_buggy.py`: the corrected Week 8 exercise.
- `debug_log.md`: the original debugging and AI-use record.
- `tests/`: eight business-rule tests and five debugging tests.

## Run

From this repository folder:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 main.py
python3 week8_buggy.py
ruff format . && ruff check . && pytest -v
```

## Import history

Imported from the combined ISM3232 coursework repository. Relevant lab commits
retain their original messages and authors; commit IDs changed during extraction.
Imports were adjusted so this repository runs on its own. The combined repository
remains the original archive. AI assisted with the original work and separation;
`debug_log.md` preserves the details of the debugging process.
