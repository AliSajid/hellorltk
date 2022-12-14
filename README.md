
# Hello RLTK

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/AliSajid/hellorltk)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/AliSajid/hellorltk)
[![Continuous integration](https://github.com/AliSajid/hellorltk/actions/workflows/ci.yaml/badge.svg?branch=main&event=push)](https://github.com/AliSajid/hellorltk/actions/workflows/ci.yaml)

This is a small project based on the
[Roguelike Tutorial - in Rust](https://bfnightly.bracketproductions.com/) series of tutorials.

## Builds

| Platform | Rust Version |Status |
| -------- | ------ | ------ |
| Linux    | stable <br/> beta <br/> nightly <br/> MSRV (1.56.1) | ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/ubuntu-stable.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/ubuntu-beta.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/ubuntu-nightly.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/ubuntu-msrv.json) |
| Windows  | stable <br/> beta <br/> nightly <br/> MSRV (1.56.1) | ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/windows-stable.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/windows-beta.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/windows-nightly.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/windows-msrv.json) |
| macOS    | stable <br/> beta <br/> nightly <br/> MSRV (1.56.1) | ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/macos-stable.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/macos-beta.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/macos-nightly.json) <br/> ![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/f490de4819ea0b8ef5e1732d17ecbbd7/raw/macos-msrv.json) |

## Current Status

As of v1.6.0 I am at Chapter 3 of the tutorial.
At this point I have a functional world where there are movable mobs and renderable player.
I have also implemented a map generation and collision system.

## License

The original tutorial is licensed under the MIT License so this project is following the same license.

You can find the [MIT License](https://choosealicense.com/licenses/mit/) here.

## Related

Here are some related projects

The original RLTK crate: [rltk](https://crates.io/crates/rltk)

The modified new crate with added functionality: [bracket-lib](https://crates.io/crates/bracket-lib)
