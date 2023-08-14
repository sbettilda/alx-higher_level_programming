##### PYTHON DATA STRUCTURES: LIST, TUPLES

0. Print a list of integers
Write a function that prints all integers of a list.

Prototype: def print_list_integer(my_list=[]):
Format: one integer per line. See example
You are not allowed to import any module
You can assume that the list only contains integers
You are not allowed to cast integers into strings
You have to use str.format() to print integers

1. Secure access to an element in a list
Write a function that retrieves an element from a list like in C.

Prototype: def element_at(my_list, idx):
If idx is negative, the function should return None
If idx is out of range (> of number of element in my_list), the function should return None
You are not allowed to import any module
You are not allowed to use try/except

2. Replace element
Write a function that replaces an element of a list at a specific position (like in C).

Prototype: def replace_in_list(my_list, idx, element):
If idx is negative, the function should not modify anything, and returns the original list
If idx is out of range (> of number of element in my_list), the function should not modify anything, and returns the original list
You are not allowed to import any module
You are not allowed to use try/except

3. Print a list of integers... in reverse!
Write a function that prints all integers of a list, in reverse order.

Prototype: def print_reversed_list_integer(my_list=[]):
Format: one integer per line. See example
You are not allowed to import any module
You can assume that the list only contains integers
You are not allowed to cast integers into strings

4. Replace in a copy
Write a function that replaces an element in a list at a specific position without modifying the original list (like in C).

Prototype: def new_in_list(my_list, idx, element):
If idx is negative, the function should return a copy of the original list
If idx is out of range (> of number of element in my_list), the function should return a copy of the original list
You are not allowed to import any module
You are not allowed to use try/except

5. Can you C me now?
Write a function that removes all characters c and C from a string.

Prototype: def no_c(my_string):
The function should return the new string
You are not allowed to import any module
You are not allowed to use str.replace(

* **6. Lists of lists = Matrix**
  * [6-print_matrix_integer.py](./6-print_matrix_integer.py): Python function that prints
  a matrix of integers, one row per line.
  * Without casting integers into strings.

* **7. Tuples addition**
  * [7-add_tuple.py](./7-add_tuple.py): Python function that adds two tuples.
  * Returns a tuple with two integers:
    * The first element is the addition of the first element of each argument.
    * The second element is the addition of the second element of each argument.
  * If a tuple is smaller than 2, the value `0` is used for the missing integer.
  * If a tuple is larger than 2, only the first two integers are used.
  * Without importing modules.

* **8. More returns!**
  * [8-multiple_returns.py](./8-multiple_returns.py): Python function that returns a
  tuple with the length of a string and its first character.
  * If the string is empty, the first character should equal `None`.
  * Without importing modules.

* **9. Find the max**
  * [9-max_integer.py](./9-max_integer.py): Python function that finds the biggest integer
  of a list.
  * If the list is empty, the function returns `None`.
  * Without importing modules or using the builtin `max()`.

* **10. Only by 2**
  * [10-divisible_by_2.py](./10-divisible_by_2.py): Python function that finds all multiples
  of 2 in a list.  * Returns a new list of the same size. Each element of the new
  list contains either `True` or `False` corresponding to whether the integer at
  the same position in the original list is a multiple of 2.
  * Without importing modules.

* **11. Delete at**
  * [11-delete_at.py](./11-delete_at.py): Python function that deletes an item at
  a specific position in a list.
  * If `idx` is negative or out of range (greater than the number of elements in
  `my_list`), the function returns the original list.
  * Without imporitng modules or using `pop()`.

* **12. Switch**
  * [12-switch.py](./12-switch.py): Python program that switches the values of
  variable `a` and `b`.
  * Completion of [this source code](https://github.com/holbertonschool/0x03.py/blob/master/12-switch_py).

* **13. Linked list palindrome**
  * [13-is_palindrome.c](./13-is_palindrome.c): C function that checks if a
  singly-linked list is a palindrome.
  * If the function is not a palindrome - returns `0`.
  * If the function is a palindrome - returns `1`.
  * An empty list is considered a palindrome.
  * Helper files:
    * [linked_lists.c](./linked_lists.c): C functions handling linked lists for
    testing [13-is_palindrome.c](./13-is_palindrome.c) (provided by Holberton School).
    * [lists.h](./lists.h): Header file containing definitions and prototypes for all types
    and functions used in [linked_lists.c](./linked_lists.c) and
    [13-insert_number.c](./13-insert_number.c).

* **14. CPython #0: Python lists**
  * [100-print_python_list_info.c](./100-print_python_list_info.c): C function that
  prints basic information about Python lists

