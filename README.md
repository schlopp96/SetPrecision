# setPrecision

## About

- `setPrecision` is a small module providing a simple way to set the precision of a floating point number or decimal to the desired amount of digits following the decimal point.

---

## Installation

### Using PIP _(Recommended)_

- To install `setPrecision` using `pip`, enter the following:

  ```python
  pip install setPrecision
  ```

- Done!

---

### Manual Installation

> _Not_ recommended.

1. Before use, navigate to intended installation location, and create a new directory.
2. Install all dependencies for this package within said directory using:

   ```python
   pip install -r requirements.txt
   ```

3. Clone repository with the git client of your preference.
   - (Optional) move installation directory to `"path/to/Python/Libs/site_packages"` to be able to import this package to a Python program like any other importable package.

- Done!

---

## Usage

- In order to use `setPrecision`, start by importing the module to your Python environment:

```python
from setPrecision import set
```

- Now, simply call the `set` method and enter your desired number to be formatted as the `digit` parameter, and the level of precision as the `precision` parameter:

```python
>>> myNumber = 3.141592653589793 # Not necessary to set number as variable.
>>> myNumber = set(myNumber, 2)
>>> print(myNumber)
'3.15'
```

> Note that the output is automatically rounded up when `digit >= 5`, and down when `digit < 5`.

- Both params can be entered in string format, and will output successfully assuming that both paramaters can be cast to their appropriate types.
  - This is done automatically.

---

## Contact the Author

- If you have any questions, comments, or concerns that cannot be alleviated through the [project's GitHub repository](https://github.com/schlopp96/setPrecision), please feel free to contact me through my email address:
  - `schloppdaddy@gmail.com`
