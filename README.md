# decimal-binary-converter
Python packge for converting decimal numbers into binary.

This package is used to provide an example of how to create a Python package. ✨

---

### How to make the package available 🙌

If necessary, use a virtual environment:
1. Add the virtual environment to the `.gitignore` file by writing `<name-of-venv>/`.
2. Set up the virtual environment using: `python -m venv <name-of-venv>`.
3. Activate the virtual environment using: `venv/Scripts/activate` (Windows).


Run the following commands:
1. Install dependencies using: `pip install setuptools wheel twine`.
2. Build source code and binary distribution wheel using: `python setup.py sdist bdist_wheel`.
3. Upload the distribution wheel to the Python package index using: `twine upload dist/*`.

---

### Details 🔎

In the `__init__.py` file, we leave it non-empty to make it easier to import stuff from the pacakge.
- Instead of having to write `from decimal_binary_converter.converter import decimal_to_binary` when importing,
- We can write `from decimal_binary_converter import decimal_to_binary`.

