# ensure-pipenv

Installs a pinned version of pipenv into the shared Python venv.

Designed to run after `ensure-pip`, which ensures pip is available
and sets `ensure_pip_virtualenv_command`.

## Role Variables

| Variable | Default | Description |
|---|---|---|
| `python_venv_dir` | `/tmp/venv` | Path to the Python venv |
| `pipenv_version` | `2026.5.2` | Version of pipenv to install |
