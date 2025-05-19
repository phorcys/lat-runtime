# README

`lat-runtime` 是在 LoongArchlinux 上运行二进制翻译软件时的运行时环境，主要是为运行
32/64 位 x86 应用（包括wine）提供运行时所需的依赖库。

本仓库使用 Archlinux (x86_64) 系统库来制作可在 LoongArchLinux 上使用的
lat-runtime-i386/lat-runtime-x86_64 运行时环境。

# 用法

在 LoongArchlinux 上执行以下命令：

```
$ ./bin/make-x86-runtime
```

最终将在当前目录生成 `lat-i386-YYYYMMDD.tar.zst` 和 `lat-i386-YYYYMMDD.tar.zst` 文件以供发布。

如需打包，请参考 [PKGBUILD](https://github.com/loongarchlinux/laur/blob/main/lat-runtime/PKGBUILD) 文件
