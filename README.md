todo.txt-count
===========

This is an add-on for [todo.txt-cli](https://github.com/todotxt/todo.txt-cli).

This add-on allows the user to easily deal with items with `count` metadata, for example `banana count:3`.

You absolutely don't want to eat one banana while marking all bananas as done (eaten); you may also not want to only be able to mark bananas as done after finishing all of them, right? This add-on is for you.

## Usage

To get help, type:

```
todo.sh count help
```

The options are hopefully clear enough.

## `count` metadata

This is a custom metadata, so you can write your todo item in whichever way you like. For example:

```
2020-01-01 very tasty long-preserving banana due:2020-12-31 count:3
```

If a todo item does not contain a `count` metadata, it is assumed to be `1` (intuitive, right?).

## Installation

Clone this repo, and copy (or create a symbolic link of) the `count` file to `~/.todo.actions.d/`.

See the [official document](https://github.com/todotxt/todo.txt-cli/wiki/Todo.sh-Add-on-Directory#installation) for more information.

