# Pre-commit

Reusable set of [pre-commit](https://pre-commit.com/) hooks; install with e.g.:

```sh
git submodule add https://github.com/klutometis/pre-commit.git
stow -v -d pre-commit -t . --dotfiles pre-commit
pre-commit install
```

and before every commit:

```sh
pre-commit run
```
