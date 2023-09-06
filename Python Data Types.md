# Python Data Types


## [Data Types Documentation](https://docs.python.org/3/library/datatypes.html)

In Python, data is categorized into various types. These types can be divided into two main categories: built-in data types and user-defined data types. Let's explore these data types:

| Category            | Data Type    | Example                    |
|---------------------|--------------|----------------------------|
| **Numeric Types**   | `int`        | 42                         |
|                     | `float`      | 3.14                       |
|                     | `complex`    | 2 + 3j                     |
| **Sequence Types**  | `str`        | "Hello, World!"            |
|                     | `list`       | [1, 2, 3]                  |
|                     | `tuple`      | (1, 2, 3)                  |
| **Mapping Type**    | `dict`       | {"name": "John", "age": 30}|
| **Set Types**       | `set`        | {1, 2, 3}                  |
|                     | `frozenset`  | frozenset([1, 2, 3])       |
| **Boolean Type**    | `bool`       | True, False                |
| **Binary Types**    | `bytes`      | b'hello'                   |
|                     | `bytearray`  | bytearray([65, 66, 67])    |
|                     | `memoryview` | memoryview(b'hello')       |
| **User-Defined**    | `class`      | CustomClass()              |


Agora, vamos prosseguir explicando cada um desses tipos de dados:

### Numeric Types

1. **int**: Represents integer numbers, e.g., 42.
2. **float**: Represents floating-point numbers, e.g., 3.14.
3. **complex**: Represents complex numbers, e.g., 2 + 3j.

### Sequence Types

4. **str**: Represents strings of characters, e.g., "Hello, World!".
5. **list**: Represents ordered, mutable sequences, e.g., [1, 2, 3].
6. **tuple**: Represents ordered, immutable sequences, e.g., (1, 2, 3).

### Mapping Type

7. **dict**: Represents key-value pairs, e.g., {"name": "John", "age": 30}.

### Set Types

8. **set**: Represents unordered, mutable collections of unique elements, e.g., {1, 2, 3}.
9. **frozenset**: Represents unordered, immutable collections of unique elements, e.g., frozenset([1, 2, 3]).

### Boolean Type

10. **bool**: Represents Boolean values, either True or False.

### Binary Types

11. **bytes**: Represents immutable sequences of bytes, e.g., b'hello'.
12. **bytearray**: Represents mutable sequences of bytes, e.g., bytearray([65, 66, 67]).
13. **memoryview**: Represents a memory view of bytes, e.g., memoryview(b'hello').

### User-Defined

14. **class**: Represents user-defined data types created using classes, e.g., `CustomClass()`.


## To understand better:
Some data types can generate doubts about their use, especially if it's the first time you've had contact with them, so let's delve a little deeper.
I'll explain the `tuple`, `list`, `set`, and `binary types` (which include `bytes`, `bytearray`, and `memoryview`) in more detail. Let's get started:
### Tuple (`tuple`)

- Description: A tuple is an ordered and immutable sequence of elements. It is similar to a list, but unlike lists, tuples cannot be changed once they have been created.
- Common Use Use tuples when you want to store a set of values that should not be modified, such as coordinates (x, y) or date information (year, month, day).
- **Example**:
  ```python
  coordinates = (3, 4)
  date = (2023, 8, 31)
  ```

### List (`list`)

- Description: A list is an ordered and mutable sequence of elements. It can contain elements of different types and allows you to add, remove and modify items.
- Common Usage: Use lists when you need to store a collection of items that can be changed, such as a list of tasks or numbers for calculations.
- Example:
  ```python
  tasks = ["Buy groceries", "Read a book", "Write code"]
  numbers = [1, 2, 3, 4, 5]
  ```

### Set (`set`)

- Description: A set is an unordered, mutable collection of unique elements. This means that a set cannot contain duplicate elements and does not maintain the order of the elements.
- Common Usage: Use sets when you need to store a set of unique values and don't care about the order, such as the list of unique words in a text.
- Example:
  ```python
  unique_words = {"apple", "banana", "orange"}
  ```

### Binary Types (`bytes`, `bytearray`, and `memoryview`)

- Description: These types are used to represent binary data, such as sequences of bytes. They are used in situations where you need to deal with data in its raw format.
- Bytes: An immutable sequence of bytes. Usually used to represent text data encoded in ASCII or UTF-8.
- **`bytearray`**: A mutable sequence of bytes. Useful when you need to modify data.
- **`memoryview`**: An object that exposes an object's memory as a sequence of bytes. It is used to access the memory of objects such as arrays.

- Common Use: These types are used in low-level situations, such as reading and writing binary files, manipulating network protocols or operating on raw data.

- Example:
  ```python
  binary_data = b'\x48\x65\x6c\x6c\x6f' # Bytes
  mutable_binary = bytearray(b'\x01\x02\x03')
  memory = memoryview(b'\x41\x42\x43')
  ```

These explanations should clarify the operation and use of these data types in Python. You can add them as a section in your article to help readers understand these essential concepts.

    

You now have an overview of the main data types in Python and their categories. This understanding will be fundamental as we move forward and explore more advanced topics. 
