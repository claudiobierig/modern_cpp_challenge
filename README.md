# moder_cpp_challenge

Implementing problems from "The Modern C++ Challenge" by Marius Bancila

https://github.com/PacktPublishing/The-Modern-Cpp-Challenge

Clean build with g++-8:

~~~sh
CURRENT_DIR=$(pwd)
mkdir -p build
cd build
rm -rf *
cmake -DCMAKE_C_COMPILER=/usr/bin/gcc-8 -DCMAKE_CXX_COMPILER=/usr/bin/g++-8 -DEXTERNAL_PATH=${CURRENT_DIR}/build/external ../
make
~~~

Clean build with clang-7:

~~~sh
CURRENT_DIR=$(pwd)
mkdir -p build_clang
cd build_clang
rm -rf *
cmake -DCMAKE_C_COMPILER=/usr/bin/clang-7 -DCMAKE_CXX_COMPILER=/usr/bin/clang++-7 -DEXTERNAL_PATH=${CURRENT_DIR}/build_clang/external ../
make
~~~
