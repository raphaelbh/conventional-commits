# Conventional Commits

[![Project Status](https://img.shields.io/static/v1?label=project%20status&message=complete&color=success&style=flat-square)](#)


Repository to show git commit pattern based on [conventionalcommits.org](https://www.conventionalcommits.org/)

> The Conventional Commits specification is a lightweight convention on top of commit messages. It provides an easy set of rules for creating an explicit commit history; which makes it easier to write automated tools on top of. This convention dovetails with SemVer, by describing the features, fixes, and breaking changes made in commit messages.

## Template

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

## Types

- **feat**: new feature
- **fix**: bug fix
- **refactor**: code refactor
- **style**: formatting changes (markup, white-space, ...)
- **build**: build related changes
- **ci**: ci changes
- **test**: add/fix tests
- **chore**: no production code change
- **docs**: change documentation

## Usage

```bash
$ git commit -m "fix: prevent racing of requests" -m "Introduce a request id and a reference to latest request."
```

## Reference

- https://www.conventionalcommits.org/

## Feedback

If you have any feedback, please contact me at raphaeldias.ti@gmail.com


[![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/raphaelbh)
[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raphaelbh/)
