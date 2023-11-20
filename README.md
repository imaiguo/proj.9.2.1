# PROJ


## 依赖

1. sqlite3

```bash
> set PKG_CONFIG_PATH=D:/devtools/sqlite.3.44.0/lib/pkgconfig;D:\devtools\crul.mingw.8.2.1\lib\pkgconfig;%PKG_CONFIG_PATH%
> set Path=D:\devtools\sqlite.3.44.0\bin;%Path%
```

2. curl
```bash
> set PKG_CONFIG_PATH=D:/devtools/sqlite.3.44.0/lib/pkgconfig;D:\devtools\crul.mingw.8.2.1\lib\pkgconfig;%PKG_CONFIG_PATH%
```

## windows上mingw64编译

```bash
> cmake .. -G Ninja -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\proj.9.2.1 -DTIFF_INCLUDE_DIR=D:\devtools\TIFF.4.6.0\include -DTIFF_LIBRARY=D:\devtools\TIFF.4.6.0\lib\libtiff.dll.a
> 
```
