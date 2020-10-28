# vizhub-libraries
Index of supported libraries for use in VizHub using ES6 `import` syntax.

This library feeds into VizHub's internal [Rollup](https://rollupjs.org/) configuration, telling it how to resolve package names to global variables introduced when including libraries via `<script>` tags.

Libraries not included here _can still be used in VizHub_, you just need to use the global variable exposed by the library.
