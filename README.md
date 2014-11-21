tetrinria
=========

A simple tetris implementation for training purpose



build in DEBUG mode
-------------------

*  mkdir build_debug
*  cd build_debug
*  cmake -DCMAKE_BUILD_TYPE=DEBUG ..
*  make
*  ./gtk/tetris-gtk

build in TEST mode
------------------

*  mkdir build_test
*  cd build_test
*  cmake -DCMAKE_BUILD_TYPE=TEST ..
*  make
*  CTEST_OUTPUT_ON_FAILURE=TRUE make test
* ./gtk/tetris-gtk
