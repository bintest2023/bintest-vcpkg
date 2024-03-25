## Instruction manual

1) Copy this code to your CMakeLists.txt

```
include(FetchContent)

FetchContent_Declare(
  bintest-FetchContent
  GIT_REPOSITORY https://github.com/bintest2023/bintest-FetchContent.git
  GIT_TAG        v1.2.28
)
  FetchContent_Populate(bintest-FetchContent)

set(variables_list ...) # list of tests wich you want to download 

include(${CMAKE_SOURCE_DIR}/build/_deps/bintest-fetchcontent-src/CmakeLists.txt)


# List if tests
# rational arrayD 
```

2) Instead of "..." add the names of the tests you want to install.

List of tests

  1) rational
  2) arrayD
  3) arrayt
  4) matrixs

3) Check if the targets are set.



