# Contributing

1. Create a folder named after the tool/vendor (e.g. `My Tool/`).
2. Add the system prompt as `Prompt.txt` and tool definitions as `Tools.json` (valid JSON).
3. Run `python3 scripts/build_index.py` to refresh `INDEX.md` and `index.json`.
4. Open a PR. CI fails if the index is stale. Files named `.json` that are not strict JSON are flagged in the index.
