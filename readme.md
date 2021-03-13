Configurable base for generating column based CSS grid

To adjust number of columns and grid dimensions and margins tweak variables

To adjust column types and style edit contents of the mixins.
Use selectors starting with ampersand (`&`). For example `&-auto` will result in output classes like `.col-auto`, `.col-md-auto`.
* `fraction-columns` - put here styles of columns that rely on `$grid-cols` fraction. Fraction number is represented by `$col-index` parameter variable. Example - `&-#{$col-index}` outputs `.col-6`, `.col-md-6`, [...].
* `special-columns` - put here styles of columns that do not rely on the fraction. Example `&-auto` outputs `.col-auto`, `.col-md-auto`, [...].
