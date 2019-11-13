# scopes-std-symbols
Small Scopes module that exports all "standard" symbols categorized, for the consumption of plugin generators.

## Usage:
Import this module into your generator and iterate on all subscopes, outputting
keyword definitions.
Most keys are named after their values, but where that wasn't possible (constants) `_` was
preprended; the values on the other hand have the exact representation necessary
to match for syntax highlighting, so you should iterate on those. All values are strings.

An example of a generator can be found in https://github.com/radgeRayden/emacs-scopes-mode.
