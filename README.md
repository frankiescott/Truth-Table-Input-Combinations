# Truth Table Input Combinations
Generates an Excel spreadsheet

To use:

`python ttic.py <# of inputs> <optional: -tf>`

By default, the table will be generated with binary values. Pass the `-tf` flag to generate 'T' and 'F' values.

Example:

`python ttic.py 3 -tf`

```
T T T
T	T	F
T	F	T
T	F	F
F	T	T
F	T	F
F	F	T
F	F	F
```
