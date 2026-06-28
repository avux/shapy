# Shapy

## Overview
Shapy is a small Python utility library for converting tabular data between four formats: SQL dump files (`.sql`), compressed SQL archives (`.sql.zip`), comma-separated values (`.csv`), and NumPy binary arrays (`.npy`). It was created in 2020 by Leo Turowski and Noah Becker as a local data-management helper. The library depends on `pandas` and `numpy` for data handling and uses only the Python standard library otherwise.

The entire project is a single module, `converter.py`, which exposes conversion functions such as `zip_to_csv`, `sql_to_npy`, `csv_to_sql`, and `npy_to_csv`, along with a simple interactive CLI entry point (`main()`). There is no package configuration file; the module is intended to be used directly as a script or imported into other Python code.

**Authors:** Leo Turowski, Noah Becker & Luciano Melodia.

A minimal package for quick data management.
