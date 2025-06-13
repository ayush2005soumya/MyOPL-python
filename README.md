# MyOPL

**MyOPL** is a simple interpreted programming language implemented in Python.  
It supports variables, functions, control flow, and modern data structures such as lists, dictionaries, sets, and tuples.

## Features

- **Variables** and **expressions**
- **Control flow:** if, for, while
- **Functions:** user-defined and built-in
- **Data structures:** List, Dict, Set, Tuple
- **Built-in functions** for data manipulation (e.g., `APPEND`, `LEN`, `DICT_KEYS`, `SET_ADD`, etc.)

## Example

```plaintext
# List
mylist = [1, 2, 3]
APPEND(mylist, 4)
PRINT(mylist)  # [1, 2, 3, 4]

# Set
s = {1, 2, 3}
SET_ADD(s, 4)
SET_REMOVE(s, 2)
PRINT(s)  # {1, 3, 4}

# Dict
d = {"a": 1, "b": 2}
PRINT(DICT_KEYS(d))    # ["a", "b"]
PRINT(DICT_VALUES(d))  # [1, 2]

# Tuple
t = (10, 20, 30)
PRINT(TUPLE_GET(t, 1)) # 20
```

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/ayush2005soumya/MyOPL-python.git
   cd MyOPL-python
   ```

2. **Run a program:**
   ```sh
   python basic.py yourscript.opl
   ```

3. **Try the REPL:**
   ```sh
   python basic.py
   ```

## Project Structure

- `basic.py` — The interpreter and language implementation
- `grammar.txt` — Language grammar rules
- `strings_with_arrows.py` — Utility for error reporting

## Built-in Functions

- `PRINT(value)`
- `APPEND(list, value)`
- `POP(list, index)`
- `EXTEND(listA, listB)`
- `LEN(list)`
- `DICT_KEYS(dict)`
- `DICT_VALUES(dict)`
- `DICT_ITEMS(dict)`
- `SET_ADD(set, value)`
- `SET_REMOVE(set, value)`
- `TUPLE_GET(tuple, index)`
- ...and more!

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License
