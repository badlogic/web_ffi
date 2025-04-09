## [0.7.5]
* Use module.wasmExports instead of module.asm if available. Fixes compatibility with emscripten 3.1.44+.

## [0.7.4]
* UTF8 extension and `Char` type.

## [0.7.3]
* More lenient exports parsing. Latest Emscripten will output additional non function exports which need to be skipped.

## [0.7.2]
* Fixed errors related to unexpected `runtimeType` names due to minifying in release builds

## [0.7.1]
* Fixing dead links

## [0.7.0]
* Initial release
* No struct support yet
* No pointer array extension support yet