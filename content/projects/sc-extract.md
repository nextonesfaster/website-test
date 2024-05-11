+++
title = "sc-extract"
description = "A very fast tool to extract graphics and decode CSVs from compressed game assets."
weight = 1

[extra]
cmd = "cat"
cmd_arg = "sc-extract.md"
toc = false
author = "nextonesfaster"
+++

`sc_extract` is a very fast tool to extract graphics and decode CSVs from compressed game assets.

Some features:

- processes `_tex.sc`, `.sc`, and `.csv` files
- supports LZMA, LZHAM, and zstd compression formats
- at least 10x times faster than similar tools
