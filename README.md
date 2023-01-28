# Контейнер для сборки приложений g++-10.2

## Примеры использования

- cmake

  ```shell
  docker run --rm -v $(pwd):/my_app -w /my_app lepota/gcc-10.2 sh -c "cmake . && cmake --build ."
  ```

- g++

  ```shell
  docker run --rm -v $(pwd):/my_app -w /my_app lepota/gcc-10.2 g++ -std=c++2a -O2 main.cpp
  ```
