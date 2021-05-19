# CS Instructor Assessment

**Task: in Python, implement a hash table with chaining collision resolution.**

You can use a linked list or Python's built-in list type for collision chaining.

As a hashing function, implement either of:

- DJB2
- FNV-1 (64-bit)

(These can be googled and copied from pseudocode.)

Implement `get`, `put`, and `delete` functionality.

* `put(key, value)` -- add a new key/value pair, or replace existing key's value
* `get(key)` -- return the value for a given key
* `delete(key)` -- remove a key/value pair

These operations should take Θ(1) average time.

Implement tests using the built-in `unittest` module.

Bonus: resize the hash table when the load factor exceeds 0.7.

Email a ZIP of the archive back to your Lambda contact. `git archive` might be useful.
