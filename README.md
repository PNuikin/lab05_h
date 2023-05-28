```sh
$ alias edit=subl
$ cd PNuikin/workspace
$ git clone https://github.com/tp-labs/lab05 projects/lab05_h
$ cd projects/lab05_h
$ git remote remove origin
$ git remote add origin https://github.com/PNuikin/lab05_h
$ mkdir third-party
$ mkdir third-party/gtest
$ git submodule add https://github.com/google/googletest third-party/gtest
$ mkdir tests
$ cd tests
$ touch test1.cpp
$ edit test1.cpp
$ cd ..
$ mkdir .github
$ mkdir .github/workflows
$ cd .github/workflows
$ touch test.yaml
$ edit test.yaml
$ cd ..
$ cd ..
$ mkdir coverage
$ cd coverage
$ touch lcov.info
$ cd ..
$ git add --all
$ git commit -m"Update README.md"
$ git push origin master
```

[![Coverage Status](https://coveralls.io/repos/github/PNuikin/lab05_h/badge.svg?branch=master)](https://coveralls.io/github/PNuikin/lab05_h?branch=master)
