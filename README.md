# 16.Python-All-functions-used-in-Python
Here is the consolidated list of all types of Python functions:
# Python Functions Overview

This table summarises various types of functions used in Python, including built-in functions, library functions, and user-defined methods.

| **Category**                | **Functions/Methods**                                                                                     | **Example Usage**                                                                 |
|-----------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| **Built-in Functions**       | `abs()`, `len()`, `print()`, `sum()`, `sorted()`, `input()`, `max()`, `min()`, `range()`                 | `abs(-5) -> 5`, `len([1, 2, 3]) -> 3`                                           |
| **Math Functions (`math`)**  | `sqrt()`, `pow()`, `factorial()`, `log()`, `sin()`, `cos()`, `pi`                                       | `math.sqrt(16) -> 4`, `math.pi -> 3.14159...`                                    |
| **OS Functions (`os`)**      | `getcwd()`, `mkdir()`, `listdir()`, `remove()`, `rename()`                                              | `os.getcwd() -> Current directory`                                              |
| **Sys Functions (`sys`)**    | `argv`, `exit()`, `path`                                                                                | `sys.exit()`                                                                    |
| **Random Functions**         | `randint()`, `random()`, `choice()`, `shuffle()`                                                       | `random.randint(1, 10) -> 7`                                                    |
| **Datetime Functions**       | `now()`, `strftime()`, `strptime()`                                                                    | `datetime.now() -> Current date/time`                                           |
| **Regex Functions (`re`)**   | `search()`, `match()`, `findall()`, `sub()`, `split()`                                                  | `re.search("pattern", "text")`                                                  |
| **JSON Functions (`json`)**  | `dumps()`, `loads()`, `dump()`, `load()`                                                                | `json.dumps({"key": "value"}) -> '{"key": "value"}'`                            |
| **Itertools**                | `permutations()`, `combinations()`, `chain()`                                                          | `list(itertools.permutations([1, 2, 3]))`                                       |
| **Pandas**                   | `DataFrame()`, `read_csv()`, `merge()`, `groupby()`                                                    | `pd.DataFrame({"A": [1, 2]})`                                                   |
| **Numpy**                    | `array()`, `mean()`, `std()`, `dot()`                                                                  | `np.array([1, 2, 3])`                                                           |
| **Special Methods**          | `__init__()`, `__str__()`, `__len__()`, `__getitem__()`                                                | `def __str__(self): return "Example"`                                           |
| **User-defined Functions**   | `def func()`, `lambda x: x * 2`                                                                        | `def my_func(x): return x * 2`                                                  |
| **Decorators**               | Custom decorators using `@decorator`                                                                   | `@my_decorator`                                                                 |
| **Generators**               | Functions using `yield`                                                                                | `def gen(): yield 1`                                                            |
| **Async Functions**          | `async def func()`                                                                                     | `async def fetch(): await task()`                                               |

---

Feel free to contribute by adding more categories or functions to this list!
