# HashMap Pattern

## Overview

Hashing is a technique used to store information so that we can retrieve it quickly.

In Python, the main hash-based data structures are:

- `dict` → stores **key-value pairs**
- `set` → stores **unique values**

The main advantage of hashing is that lookup, insertion, and deletion are **O(1) on average**.

---

## Why Do We Use Hashing?

Hashing is useful when we repeatedly need to:

- Check whether an element already exists
- Store previously seen elements
- Count frequencies
- Find duplicates
- Store relationships such as `value → index`
- Avoid repeated searching through an array

### Brute Force vs Hashing

For example, if we need to search for an element in an unsorted array:

```text
Array search → O(n)
