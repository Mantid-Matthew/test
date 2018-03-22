# Jenkins test

Job order:
- `clang-format`
- `cppcheck`
- `flake8`
- parallel
  - `doxygen`
  - `osx`
  - `rhel7`
  - `ubuntu`
  - `ubuntu-python3`
  - `win7`
