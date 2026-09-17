# IS 218 Test 1

## Student

Suman Kanda

## Project Purpose

This project implements and tests basic calculator operations using Python and pytest. It includes addition and subtraction functions along with student-written tests and supplied acceptance checks.

## Setup

Create a local virtual environment:

```bash
python3 -m venv .venv
```

Activate the virtual environment:

```bash
source .venv/bin/activate
```

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

The `.venv` directory is kept local and ignored by Git because virtual environments are machine-specific and can be recreated from `requirements.txt`. The `requirements.txt` file is committed so the project's required dependencies can be installed consistently on another computer.

## Testing

Run the student tests:

```bash
python -m pytest
```

Run the student tests and supplied acceptance checks:

```bash
python -m pytest tests checks -v
```

## Issues

- [Issue #1 - Set up a reproducible Python project](https://github.com/ItxSue/is218_test1_official/issues/1)
- [Issue #2 - Implement and test addition](https://github.com/ItxSue/is218_test1_official/issues/2)
- [Issue #3 - Implement and test subtraction](https://github.com/ItxSue/is218_test1_official/issues/3)
- [Issue #4 - Document, verify, and deliver](https://github.com/ItxSue/is218_test1_official/issues/4)

## Assertion Explanation

The assertion `assert add(2, 3) == 5` verifies that the `add` function correctly calculates and returns the sum of its two arguments. In this test, the inputs are `2` and `3`, and the expected result is `5`. If the function returns a value other than `5`, the assertion fails and pytest reports the test as failed.