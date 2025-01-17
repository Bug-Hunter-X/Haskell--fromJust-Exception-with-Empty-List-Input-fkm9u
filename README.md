# Haskell fromJust Exception with Empty List Input

This repository demonstrates a common Haskell error involving the `fromJust` function and empty lists. The code attempts to process a list of `Maybe` values using `fromJust` without checking for `Nothing` values, leading to a runtime exception when the input list is empty.

The `bug.hs` file contains the erroneous code, while `bugSolution.hs` provides a corrected version that handles the empty list case gracefully using pattern matching.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Compile and run `bug.hs` using a Haskell compiler (like GHC): `ghc bug.hs && ./bug`
4. Observe the runtime error.
5. Compile and run `bugSolution.hs`: `ghc bugSolution.hs && ./bugSolution`
6. Note that the corrected code handles the empty list case without errors.