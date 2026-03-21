# Cat-Reloaded Advanced A1 — Assignments

This repository is a hub for my **Cat Reloaded Advanced A1** work.
It is organized using **Git submodules**, where each assignment/task lives in its own separate repository and is included here as a submodule.

## Repository Structure

```
Cat-Reloaded_AdvancedA1/
├── README.md
├── .gitmodules
├── assignment1/              # submodule
├── assignment2/              # submodule
└── Task_entry_advancedA1/    # submodule
```

## Included Work (Submodules)

| Folder | In this repo | Source Repository |
|--------|--------------|------------------|
| `assignment1` | [./assignment1](./assignment1) | https://github.com/KenzyFrhat/Week1-2 |
| `assignment2` | [./assignment2](./assignment2) | https://github.com/KenzyFrhat/Week3 |
| `Task_entry_advancedA1` | [./Task_entry_advancedA1](./Task_entry_advancedA1) | https://github.com/KenzyFrhat/SuperMarketSales---Advanced-Starting |

## How to Clone (with Submodules)

Clone this repository **and initialize submodules**:

```bash
git clone --recurse-submodules https://github.com/KenzyFrhat/Cat-Reloaded_AdvancedA1.git
```

If you already cloned it without submodules:

```bash
git submodule update --init --recursive
```

## Working on an Assignment

Enter the submodule folder you want to work on:

```bash
cd assignment1
git status
git log
```

> Note: Since each assignment is a separate repository, commits made inside a submodule belong to that submodule repo.

## Notes

- `.gitmodules` defines the mapping between each folder and its upstream repository.
- This repo is mainly an organizer/entry point for the Advanced A1 tasks.