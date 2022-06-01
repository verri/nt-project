# Compilar no modo debug

```sh
cmake -H. -Bbuild-debug -DCMAKE_BUILD_TYPE=Debug
cmake --build build-debug
```

# Compilar no modo release

```sh
cmake -H. -Bbuild-release -DCMAKE_BUILD_TYPE=Release
cmake --build build-release
```

# Outro exemplo

```sh
cmake -H. -Bbuild -DCMAKE_BUILD_TYPE=Release -DCMAKE_CXX_FLAGS="-O2" -DCMAKE_CXX_LINK_FLAGS="-s"
cmake --build build
```
