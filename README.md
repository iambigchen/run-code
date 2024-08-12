
- 构建 C++ 镜像

  ```bash
    cd server/src/docker/cpp
    docker build -t cpp:11 .
  ```

- 构建 rust 镜像

  ```bash
    cd server/src/docker/rust
    docker build -t rust:lts .
  ```

- 构建 python3 镜像

  ```bash
    cd server/src/docker/python3
    docker build -t python:3 .
  ```

- 构建 python2 镜像

  ```bash
    cd server/src/docker/python2
    docker build -t python:2 .
  ```

- 构建 go 镜像

  ```bash
    cd server/src/docker/go
    docker build -t go:lts .
  ```

- 构建 nodejs 镜像

  ```bash
    cd server/src/docker/nodejs
    docker build -t nodejs:lts .
  ```

- 构建 java 镜像

  ```bash
    cd server/src/docker/java
    docker build -t java:lts .
  ```

- 构建 C# 镜像

  ```bash
    cd server/src/docker/dotnet
    docker build -t mono:lts .
  ```

- 构建 php 镜像

  ```bash
    cd server/src/docker/php
    docker build -t php:8 .
  ```