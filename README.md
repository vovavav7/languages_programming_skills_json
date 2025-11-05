# Languages, Programming Languages, and Skills JSON

This repository contains JSON files with data for:

- **Languages** – human languages that people can speak.
- **Programming Languages** – popular programming languages.
- **Skills** – technical skills commonly used in software development and IT.

## Files

- `languages.json` – list of human languages.
- `programming_languages.json` – list of programming languages.
- `skills.json` – list of technical skills.

## Usage

You can use these JSON files in Python/Django projects to load data into your models:

```python
import json

with open('languages.json', 'r', encoding='utf-8') as f:
    languages = json.load(f)

with open('programming_languages.json', 'r', encoding='utf-8') as f:
    programming_languages = json.load(f)

with open('skills.json', 'r', encoding='utf-8') as f:
    skills = json.load(f)
