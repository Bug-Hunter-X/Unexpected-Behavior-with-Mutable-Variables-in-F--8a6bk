# Unexpected Behavior with Mutable Variables in F#

This example demonstrates a potential issue in F# where changes to mutable variables after they are used in a function call can lead to unexpected behavior.  The `add` function uses the initial values of `x` and `y`, but subsequent modifications to these variables do not affect the function's initial output. However, this can easily lead to subtle errors in more complex scenarios.