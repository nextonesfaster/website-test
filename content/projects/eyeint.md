+++
title = "eyeint"
description = "A command line app to inspect arbitrary sized integers without various settings."
weight = 2

[extra]
cmd = "cat"
cmd_arg = "eyeint.md"
toc = false
project_home = "https://github.com/nextonesfaster/eyeint"
+++

eyeint (`ii`) is a command line app to inspect arbitrary sized integers without various settings.

`eyeint` has the following features:

- Inspects integers with an arbitrary number of bits (up to 64)
- Converts arbitrary radix (2-36) integers into most common integer radices
  - binary
  - octal
  - decimal
  - hexadecimal
- Handles signed integers
- Truncates and (sign/zero) extends integers with arbitrary bit precision
- Shows information about an integer's two's complement
