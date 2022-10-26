+++
title = "lzham"
description = "high-level Rust bingings for lzham codec"
weight = 6

[extra]
cmd = "cat"
cmd_arg = "lzham.md"
toc = false
author = "AriusX7"
project_home = "https://github.com/AriusX7/lzham"
+++

High-level Rust bindings for [lzham codec][lzham] built upon the lower-level [`lzham-sys`] crate.

You must have `cmake` and a C++ compiler to build this crate, as the `lzham-sys` crate builds `lzham` library and does not search for a prebuilt library.

[lzham]: https://github.com/richgel999/lzham_codec
[`lzham-sys`]: https://github.com/AriusX7/lzham-sys
