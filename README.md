# senior-project-practice

A practice repository for Senior Project, used to get comfortable with Git,
GitHub, and branching before the main project work begins.

## Developer Profile

`App.py` prints a short profile card:

- **Name:** Name
- **Major:** major
- **Technology Interest:** Tech Interest
- **Skill Goal:** Skill Goal

## Running it

Requires Python 3.

```bash
python3 App.py
```

Expected output:

```
Senior Project Developer Profile

Name: "name
Major: "Major"
Technology Interest: "Tech interest"
Skill Goal: "Skill goal"
```

## Repository structure

```
senior-project-practice/
├── App.py      # developer profile program
└── README.md   # this file
```

## Branching

Work happens on feature branches and is merged into `main` through pull requests.

```bash
git switch -c feature/<short-description>   # start a new branch
git push -u origin feature/<short-description>
```
