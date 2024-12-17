# F# Immutability Gotcha: Unexpected Mutation

This example demonstrates a common error in F# related to the language's immutability.  Many programmers coming from mutable languages struggle initially with this aspect of F#.

The issue arises from an assumption that the `addOne` function modifies the value of `x` in place. In F#, values are immutable; `addOne` creates a *new* value and doesn't alter the original `x`.

The code and a solution are provided.