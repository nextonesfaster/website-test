+++
title = "opentag"
description = "A command-line tool that opens a tagged path or URL using the configured system program."
weight = 4

[extra]
cmd = "cat"
cmd_arg = "opentag.md"
toc = false
project_home = "https://github.com/nextonesfaster/opentag"
+++

`opentag` (binary name: `ot`) is a command-line tool that opens a tagged path or URL using the configured system program.

The tags are added to the application as "subcommands" at run-time and appear in the help text.

`opentag` is useful when you have a bunch of websites and files you regularly open. Instead of adding bookmarks to different browsers and navigating through your file system or typing the file paths and URLs by hand each time, you can simply add them as tags and instantly open them with a short command. Tags can be grouped as subtags, which can have even more subtags! You can also provide helpful descriptions for each tag.
