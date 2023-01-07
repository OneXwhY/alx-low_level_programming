0x1A. C - Hash tables



Python Dictionaries Python dictionaries are implemented using hash tables. When you will be done with this project, you will be able to better understand the power and simplicity of Python dictionaries. So much is actually happening when you type d = {'a': 1, 'b': 2}, but everything looks so simple for the user. Python doesn’t use the exact same implementation than the one you will work on today though. If you are curious on how it works under the hood, here is a good blog post about how dictionaries are implemented in Python 2.7 (not mandatory).



Note that all dictionaries are not implemented using hash tables and there is a difference between a dictionary and a hash table. Read more here (not mandatory).



0-hash_table_create.c - a function that creates a hash table. 1-djb2.c - hash function implementing the djb2 algorithm. 2-key_index.c - a function that gives you the index of a key. 3-hash_table_set.c - a function that adds an element to the hash table. 4-hash_table_get.c - a function that retrieves a value associated with a key. 5-hash_table_print.c - a function that prints a hash table. 6-hash_table_delete.c - a function that deletes a hash table. 100-sorted_hash_table.c - writing a function using the following data structures
