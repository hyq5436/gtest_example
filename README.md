cmake -S . -B build
或者
cmake -S . -G "Ninja" -DCMAKE_BUILD_TYPE:STRING="Debug" -B build

cmake --build build