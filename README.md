# Intent-Driven Software Engineering Companion Code

This repository contains companion code for the book _Intent-Driven Software Engineering_.

The code listings are organized by chapter. Some chapter-specific listings are included as Git submodules so each example project can keep its own independent Git history.

## Cloning This Repository

To clone this repository with all chapter submodules:

```sh
git clone --recurse-submodules https://github.com/intent-driven-dev/Intent-Driven-Software-Engineering.git
```

If you have already cloned the repository without submodules, initialize them with:

```sh
git submodule update --init --recursive
```

Each submodule can be opened like a normal Git repository. You can inspect its commits, branches, and history independently from this companion repository.
