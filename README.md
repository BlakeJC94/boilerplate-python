# PLACEHOLDER
Short description here.

## Installation
Clone the repo to your system and install

```bash
$ git clone https://github.com/PLACEHOLDER
$ cd PLACEHOLDER
$ pip install .
```

## Quickstart
TODO

## Future developments
TODO

## Contributing
Pull requests are most welcome!

* Code is styled using `[black](https://github.com/psf/black)` (`pip install black`)
* Code is linted with `pylint` (`pip install pylint`)
* Requirements are managed using `pip-tools` (run `pip install pip-tools` if needed)
    * Add dependencies by adding packages to `setup.py` and running
        `pip-compile --annotation-style=line`
    * Add dev dependencies to `setup.py` under `extras_require` and run
        `pip-compile --annotation-style=line --extra=dev --output-file=requirements-dev.txt setup.py`
* [Semantic versioning](https://semver.org) is used in this repo (shockingly)
    * Major version: rare, substantial changes that break backward compatibility
    * Minor version: most changes - new features, models or improvements
    * Patch version: small bug fixes and documentation-only changes

Virtual environment handling by `pyenv` is preferred:
```bash
# in the project directory
$ pyenv virtualenv 3.9.7 PLACEHOLDER
$ pyenv local PLACEHOLDER
$ pip install -e .
```
