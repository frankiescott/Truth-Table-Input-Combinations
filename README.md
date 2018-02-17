# Truth Table Input Combinations
Generates all possible input combinations for a truth table and stores the table in an Excel spreadsheet.

To use:

`python ttic.py <# of inputs> <optional: -tf>`

By default, the table will be generated with binary values. Pass the `-tf` flag to generate 'T' and 'F' values.

Examples:

`python ttic.py 3 -tf`

```
A	B	C
T	T	T
T	T	F
T	F	T
T	F	F
F	T	T
F	T	F
F	F	T
F	F	F
```

`python ttic.py 4`

```
A	B	C	D
0	0	0	0
0	0	0	1
0	0	1	0
0	0	1	1
0	1	0	0
0	1	0	1
0	1	1	0
0	1	1	1
1	0	0	0
1	0	0	1
1	0	1	0
1	0	1	1
1	1	0	0
1	1	0	1
1	1	1	0
1	1	1	1
```
