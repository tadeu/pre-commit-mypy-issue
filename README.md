# pre-commit-mypy-issue
Example of a problem where `pre-commit mypy` behaves differently than `mypy`

```
# Create and activate environment:
$ python -m venv create .venv
$ source .venv/bin/activate  # or, in Windows: .venv\Scripts\activate
$ python -m pip install --upgrade pip==20.2.4
$ pip install -r requirements.txt

# Run stand-alone mypy:
$ mypy

# Run mypy via pre-commit:
$ pre-commit run mypy -a
```
