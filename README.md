# pkgnet for Python

> [!IMPORTANT]
> This is an **experimental** port of the [pkgnet](https://github.com/uptake/pkgnet) R package to Python for analysis of Python packages.

**pkgnet** is a Python library designed for the analysis of Python libraries! The goal of the package is to build a graph representation of a package and its dependencies to inform a variety of activities, including:

- prioritizing functions to unit test based on their centrality
- examining the recursive dependencies you are taking on by using a given package
- exploring the structure of a new package provided by a coworker or downloaded from the internet

## How it Works

The core functionality of this package is the CreatePackageReport function.

## Installation

This package is not yet available via PyPI. You will need to clone this repository and install from source:

```bash
pip install .
```

## Usage Examples

Try it out!

```python
from pkgnet import create_package_report
create_package_report("jinja2")
```
