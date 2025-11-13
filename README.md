# container-test-01

## Setup

devcontainer.json is inspired by
- [uv-issue discussion](https://github.com/astral-sh/uv/issues/12197)

Setup ssh-agent in your host machine

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

## Start Jupyter Lab

```bash
uv run jupyter-lab

