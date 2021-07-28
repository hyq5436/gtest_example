生成构建脚本
cmake -S . -B build
或者
cmake -S . -G "Ninja" -DCMAKE_BUILD_TYPE:STRING="Debug" -B build

编译
cmake --build build

运行
cd build && ctest && cd ..