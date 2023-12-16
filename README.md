# QWindowKit

Cross-platform window customization framework for Qt Widgets and Qt Quick.

This project inherited most of [FramelessHelper](https://github.com/wangwenx190/framelesshelper)'s implementation, with a complete refactoring and upgrading of the architecture.

## Supported Platforms

+ Microsoft Windows (Vista ~ 11)
+ Apple Mac OSX (11+)
+ GNU/Linux (Tested on Ubuntu)

## Requirements

| Component | Requirement |               Detailed               |
|:---------:|:-----------:|:------------------------------------:|
|    Qt     |   \>=5.15   |      Core, Gui, Widgets, Quick       |
| Compiler  |  \>=C++17   |        MSVC 2019, GCC, Clang         |
|   CMake   |   \>=3.17   |        >=3.20 is recommended         |

### Tested Compilers

+ Windows
  + MSVC: 2019, 2022
  + MinGW: 13.2.0
+ MacOSX
  + Clang 14.0.3
+ Ubuntu
  + GCC: 9.4.0

## Dependencies

+ [qmsetup](https://github.com/stdware/qmsetup)

## Quick Start

This project relies heavily on `qmsetup`, which must be installed for CMake Configue to succeed. If you do not install `qmsetup` or specify a valid `qmsetup_DIR`, `qmsetup` will be automatically pulled from remote repository and installed in the current directory. You can disable this behavior by setting `QWINDOWKIT_DISABLE_FETCH_PACKAGES`. You can also clone `qmsetup` to the current directory in advance.

```sh
git clone https://github.com/stdware/qmsetup.git
```
```sh
git clone git@github.com:stdware/qmsetup.git
```


## Documentatons

+ Examples (TODO)
+ [Framelesshelper Related](docs/framelesshelper-related.md)

## License

QWindowKit is licensed under the [Apache 2.0 License](LICENSE).