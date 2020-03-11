# Cookiecutter template for Git Repos

This repo contains a Cookiecutter template which helps to generate a Git Repo.

## Getting Started

```bash
pip install cookiecutter
cookiecutter https://github.com/fiftyonefifty/cookiecutter-git-repo
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Versioning

This project uses semantic versioning ([SemVer 2.0.0](https://semver.org/)). Incrementing versions is managed by [bumpversion](https://github.com/peritus/bumpversion).

To ensure that the repo is properly versioned, you will need to install `bumpversion`.

```bash
pip install bumpversion
```

Once installed, bump the version before pushing your code or created a pull request.

```bash
# Examples

# Bumping the major version to indicate a backwards incompatible change
bumpversion major

# Bumping the minor version
bumpversion minor

# Bumping the subminor due to a hotfix
bumpversion patch
```

