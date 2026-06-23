# yaml-config-loader

Minimal YAML config loader with `${ENV_VAR}` interpolation. Built on PyYAML.

## Usage

```python
from config_loader import load_config
cfg = load_config("config.yml")
print(cfg["database"]["host"])
```

## Interpolation

Values like `${HOME}` are replaced from environment variables at load time.

## Dependencies

See `requirements.txt`.