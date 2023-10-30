# README

`lat-runtime` 是在 LoongArchlinux 上运行二进制翻译软件时的运行时环境，主要是为运行
32/64 位 x86 应用（包括wine）提供运行时所需的依赖库。

本仓库使用 Archlinux (x86_64) 系统运行时库来制作可在 LoongArchLinux 上使用的
lat-runtime-i386/lat-runtime-x86_64 运行时环境。

# 用法

```
$ ../bin/make-x86-runtime
```
