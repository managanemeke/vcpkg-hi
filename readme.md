# vcpkg-hi

## initialize-new-application

```shell
vcpkg new --application
```

## add-new-dependency

```shell
vcpkg add port fmt
```

## build-via-msvc

```shell
mkdir build
```

```shell
cd build
```

```shell
cmake .. -G "Visual Studio 17 2022" -DCMAKE_C_COMPILER="C:/Program Files (x86)/Microsoft Visual Studio/2022/BuildTools/VC/Tools/MSVC/14.44.35207/bin/Hostx64/x64/cl.exe" -DCMAKE_CXX_COMPILER="C:/Program Files (x86)/Microsoft Visual Studio/2022/BuildTools/VC/Tools/MSVC/14.44.35207/bin/Hostx64/x64/cl.exe" -DCMAKE_TOOLCHAIN_FILE="C:/Users/ha/home/vcpkg/scripts/buildsystems/vcpkg.cmake"
```

Links:
* [get-started](https://learn.microsoft.com/en-us/vcpkg/get_started/get-started?pivots=shell-powershell)
