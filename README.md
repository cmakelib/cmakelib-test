
# CMake Lib test repository for CMake Lib tests

Testing files for CMake-lib nit and integration tests.

This repository is hosted in Github and Gitlab (Github does not support `git archive`)

- https://github.com/cmakelib/cmakelib-test
- https://gitlab.com/cmakelib/cmakelib-test

## Branches

There are two branches

- master
- test-branch

each branch has same directory structure regardless cmake/|cmake-test/ directory,

```
dir_a --> test_branch_dir_a
dir_b --> test_branch_dir_b
same --> test_branch_same
```

`dir_a`, `dir_b` contains different files in both branches.

`same/` contains equivalent file in both branches.

### master branch

cmake/dir_a/test.zip contains following files

- Release_CMake.png
- cmake1.png

### test-branch branch

cmake/dir_a/test.zip contains following files

- Release_CMake.png
- cmake1.png
- General CI_CD.png
