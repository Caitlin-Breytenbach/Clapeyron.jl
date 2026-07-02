# v0.6.26

## New Features

- Automatic Differentiation: custom tag types are now used on most bulk properties, allowing a reduction in precompile times, specially when using multiple models at once.
- New method: `is_idealmodel`, that checks if a model is a model of an ideal gas or not.
- Most methods expected to be used and extended by users of Clapeyron.jl are now marked as `public`. Methods not marked as public are considered internal.

## Bug Fixes

- Symbolics extension bug fixes.
- Misc stability improvements
