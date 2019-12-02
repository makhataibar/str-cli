str-cli
=======

React CLI

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/str-cli.svg)](https://npmjs.org/package/str-cli)
[![Downloads/week](https://img.shields.io/npm/dw/str-cli.svg)](https://npmjs.org/package/str-cli)
[![License](https://img.shields.io/npm/l/str-cli.svg)](https://github.com/makhataibar/str-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g str-cli
$ str COMMAND
running command...
$ str (-v|--version|version)
str-cli/0.0.0 linux-x64 node-v10.16.3
$ str --help [COMMAND]
USAGE
  $ str COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`str hello [FILE]`](#str-hello-file)
* [`str help [COMMAND]`](#str-help-command)

## `str hello [FILE]`

describe the command here

```
USAGE
  $ str hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ str hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/makhataibar/str-cli/blob/v0.0.0/src/commands/hello.ts)_

## `str help [COMMAND]`

display help for str

```
USAGE
  $ str help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src/commands/help.ts)_
<!-- commandsstop -->
