# clang

## Enforcing the following guidelines:

### clang-tidy:
* Max method statements: 30 lines (Closest estimation to function length)
* No magic numbers allowed
* macros (defines) are UPPER_CASE
* variables are lower_case
* function names are camelCase
* structs are CamelCase
* allowed headers according to exercise
* disabled checks for unsafe functions such as scanf, strcmp
* disabled initialize checks (personal preference)

### clang-format:
* Column width: 80
* Indentation: tab width is 4, never use tabs
* Always breaks before braces (personal preference)
* Disabled argument BinPacking (Each argument will have it's own line)
* int\* a instead of int \*a

### Test env:

LLVM (http://llvm.org/):
  LLVM version 11.0.0
  Optimized build.
  Default target: x86_64-pc-windows-msvc
  Host CPU: skylake

Also tested on Ubuntu 20.04.