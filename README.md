# Prerequisites

- Docker

# Debug

```PowerShell
docker run -it --rm -v ${PWD}:/workplace -w /workplace python:3.12.0-alpine3.18 sh
```

```sh
python sample.py
```

# Launching

```PowerShell
docker run -it --rm -v ${PWD}:/workplace -w /workplace python:3.12.0-alpine3.18 sh -c "python sample.py"
```
