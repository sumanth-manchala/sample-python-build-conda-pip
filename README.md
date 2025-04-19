# Sample Python Build with Conda and Pip

This project demonstrates how to build .conda and .whl builds for pure python packages.

## Features

- Build Conda packages using `pixi build`.
- Build Python wheels using `uv build`.

## Prerequisites

Ensure you have the following installed:

- `pixi` (a Conda build tool) - [Installation Guide](https://pixi.sh/latest/#installation)
- `uv` (a Python wheel build tool) - [Installation Guide](https://docs.astral.sh/uv/getting-started/installation)

## Build Instructions

### Build Conda Package

To build the Conda package, run the following command:

```bash
pixi build
```

This will generate a Conda package in the `dist/` directory.

### Build Python Wheel

To build the Python wheel, run the following command:

```bash
uv build
```

This will generate a `.whl` file in the `dist/` directory.