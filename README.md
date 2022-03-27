#  Learning how to data engineer

## Introduction

The first step in most data analytics projects is reading the data file. In this exercise, you'll create Series and DataFrame objects, both by hand and by reading data files.

Run the code cell below to load libraries you will need (including code to check your answers).

```python
add Codeadd Markdown
import pandas as pd
pd.set_option('max_rows', 5)
from learntools.core import binder; binder.bind(globals())
from learntools.pandas.creating_reading_and_writing import *
print("Setup complete.")
```

### Exercise #1
In the cell below, create a DataFrame fruits that looks like this:
|   | Apples | Bananas |
|   | ------ | ------- |
| 0 |   30   |    31   |


