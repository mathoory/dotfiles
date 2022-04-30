# clang

## Enforcing the following guidelines:

### clang-tidy:
* Max method statements: 13 lines (as close as we can get to course guidelines.)
* No magic numbers allowed
* macros (defines) are UPPER_CASE
* allowed headers according to exercise
* disabled checks for unsafe functions such as scanf, strcmp
* disabled checks for possible 'const' arguments, not used in this course
* disabled declaration isolation (saves lines of code)
* disabled initialize checks (personal preference)

### clang-format:
* Column width: 75
* Indentation: tab width is 4, never use tabs
* Always breaks before braces (personal preference)
* Disabled argument BinPacking (Each argument will have it's own line)

### Test env:

LLVM (http://llvm.org/):
  LLVM version 11.0.0
  Optimized build.
  Default target: x86_64-pc-windows-msvc
  Host CPU: skylake