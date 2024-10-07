# python-wrapper-script

Small project template for quick prototyping and testing.

## Prerequisites

For this script to work, you need the following things:
- `Python 3.*`
- `main.sh` and `main.py` should have the same basename (whatever that is)

## Dependencies

Add your packages in `requirements.txt`.
Run `install.sh` to initialise the folder or update the dependencies.

## Environment variables

Any file starting with `.env` will be loaded in the environment before invoking the Python script.

A good practice is to split the variables in two files:
- `.env.shared` for any public variable (this file can be added to the source control)
- `.env.secret` for any private secret (this file SHOULD never be added to the source control)

## Command line arguments & stdin

Executing the wrapper script will properly forward command line arguments and stdin.
