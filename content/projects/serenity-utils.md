+++
title = "serenity-utils"
description = "A library to provide conversions, prompts and menu functionality for Discord bots created with serenity."
weight = 2

[extra]
cmd = "cat"
cmd_arg = "serenity-utils.md"
toc = false
project_home = "https://github.com/nextonesfaster/serenity-utils"
+++

A library to provide conversions, prompts and menu functionality for Discord bots created with [serenity-rs](https://github.com/serenity-rs/serenity).

This library provides implementations to easily:

- Get user response using message or reaction prompts.
- Display paginated reaction-based messages/menus.
- Format text in different ways before sending.
- ~~Convert a string to serenity's guild-specific models.~~ (deprecated; use serenity's ArgumentConvert trait instead)
- ~~Create embeds and messages with field access.~~ (deprecated; use serenity's builder directly)
