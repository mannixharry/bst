# Balanced Search Trees

Jupyter notebooks implementing AVL, Left-Leaning Red-Black (LLRB), and 2-3
trees over string keys. Each provides search, insert and delete, alongside a
statistics framework for comparing their empirical performance.

## Contents

- **TwoThreeTree.ipynb** - 2-3 tree (insert, search, delete).
- **AVLTree.ipynb** - AVL tree (insert, search, delete).
- **LeftLeaningRedBlackTree.ipynb** - LLRB tree (insert, search, delete).
- **Stats.ipynb** - a `StatisticsFramework` class providing mean, variance,
  standard deviation and standard error, logarithmic regression and
  goodness-of-fit, used to check empirically that tree operations run in
  O(log N) time.

Each tree implements a shared `AbstractSearchInterface` (`insertElement`,
`searchElement`), defined at the top of its notebook. Delete is provided as an
additional method outside that interface.
- **Report.pdf** - the group's write-up of the comparison.

## Status

This was my contribution to a group research project comparing the three tree
types. The full repository is at
https://github.com/xpzhxhm/AlgorithmCoursework - in that version we dropped the
delete operations, and used AVL and LLRB implementations that my teammates
developed independently.