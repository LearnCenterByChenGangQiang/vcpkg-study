# vcpkg 使用方法

## 1. 创建项目
```sh
mkdir helloworld && cd helloworld
```

## 2. 初始化 vcpkg
```sh
vcpkg new --application
```

## 3. 添加依赖
```sh
vcpkg add port fmt
```

## 4. 安装依赖
```sh
vcpkg install
```


## 5. 创建 CMakeLists.txt

## 6. 创建 CMakePresets.json

# 配置和构建
## mac
```sh
cmake --preset mac-xcode .
cmake --build build/mac-xcode --config Release
```

```sh
cmake --preset mac-ninja .
cmake --build build/mac-ninja --config Release
```

## windows
```sh
cmake --preset windows-ninja .
cmake --build build/windows-ninja --config Release
```
```sh
cmake --preset windows-vs2022 .
cmake --build build/windows-vs2022 --config Release
```

