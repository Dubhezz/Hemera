# Hemera

Hemera is a development tool.

## Installation

use gem

```
gem install hemera
```

## Usage

use help to see details

```
hm help

NAME
    hm - Hemera, a command line tool for development

SYNOPSIS
    hm [global options] command [command options] [arguments...]

VERSION
    0.1.1

GLOBAL OPTIONS
    --help    - Show this message
    --version - Display the program version

COMMANDS
    help     - Shows a list of commands or help for one command
    meta, m  - metaprogramming
    pod, p   - cocoapods
    xcode, x - Xcode
```
use meta to generate code
```
hm meta

NAME
    meta - metaprogramming

SYNOPSIS
    hm meta img <fileName> <path>

COMMANDS
    img, i - generate img code
```
![command_meta](resource/meta_command.gif)

use xcode subcommand can open/clean workspace

```
# Clean DerivedData, support custom path
hm xcode clean # also hm x c

# Open Xcode Workspace, support xcodeproj and xcworkspace
hm xcode open # also hm x o
```

use pod can create/install with cocoapods

```
# create a pod
hm pod create YourPodsName # also hm p c YourPodsName

# force install podfile when pod install error
hm pod install # also hm p i
```

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Hemera project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/hemera/blob/master/CODE_OF_CONDUCT.md).
