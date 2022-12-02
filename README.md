# Santa's Allotment Kata

Santa wants to plant `n` evergreen Christmas trees in his allotment. His allotment is always a square of `n` plots by
`n` plots. One plot may contain a Christmas tree. However, because of their magical root structure these evergreen trees
will not grow if there is another one horizontally or diagonally aligned with the tree. For example, given `n = 4` and
if we represent a tree with `O` and an empty lot with `-` then the following is **valid**:

```
-O--
---O
O---
--O-
```

The following are **invalid**:

```
OOOO
----
----
----
```

```
O---
O---
O---
O---
```

```
O---
-O--
--O-
---O
```

Given a size `n`, try to find a solution for placing the trees in an allotment of size `n`. If there is no valid
solution, return an empty array:

```
[]
```

If there is a valid solution, return an array with a number for each column of the allotment equal to the height (aka
the Y value), where the top of the allotment is 0, of the one tree on that column. For example, in our valid solution at
the top, the answer would be:

```
[2,0,3,1]
```
