# Haskell Sort Function Behavior

This repository demonstrates a common misconception regarding Haskell's `sort` function from `Data.List`. Many programmers from imperative backgrounds expect `sort` to modify the original list, similar to how `sort` might behave in languages like Python or JavaScript. However, in Haskell, `sort` is a pure function; it returns a *new* sorted list without altering the original list.  This example highlights this important distinction.

**To run the code:**
1. Make sure you have the Haskell compiler (GHC) installed.
2. Save the code in `bug.hs` and `bugSolution.hs`
3. Compile and run using `ghc bug.hs && ./bug`
4. Repeat for `bugSolution.hs`
