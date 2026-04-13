# Cat-Reloaded Advanced A1 — Assignments

This repository collects and organizes my assignments for the **Cat Reloaded — Advanced A1** phase.

## Goal

Track, organize, and share all assignments completed during the Advanced A1 training phase.

This repository is organized using **Git submodules** — each assignment/task lives in its **own separate repository** and is included here as a submodule folder.  
That means each folder has its own commit history and remote repository.

## Structure

```
Cat-Reloaded_AdvancedA1/
├── README.md
├── .gitmodules
├── Task_entry_advancedA1/    # submodule (starting task)
├── assignment1/              # submodule (Week 1–2)
├── assignment2/              # submodule (Week 3)
├── Assignment3/              # submodule (Week 3 optional)
```

## Included Work (Submodules)

| Folder | In this repo | Source Repository |
|--------|--------------|------------------|
| `Task_entry_advancedA1` | [./Task_entry_advancedA1](./Task_entry_advancedA1) | https://github.com/KenzyFrhat/SuperMarketSales---Advanced-Starting |
| `assignment1` | [./assignment1](./assignment1) | https://github.com/KenzyFrhat/Week1-2 |
| `assignment2` | [./assignment2](./assignment2) | https://github.com/KenzyFrhat/Week3 |
| `Assignment3` | [./Assignment3](./Assignment3) |(https://github.com/KenzyFrhat/Student_Performance/commit/3efce0b557b653327d5950abab704bde9492da40) |


## How to Clone (with Submodules)

Clone this repository and initialize submodules:

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

> Note: Commits made inside a submodule belong to that submodule repository.  
> To update what commit the main repo points to, commit the submodule pointer change in the main repo.

## Notes

- `.gitmodules` defines the mapping between each submodule folder and its upstream repository.
- This repository is mainly an organizer/entry point for the Advanced A1 tasks.