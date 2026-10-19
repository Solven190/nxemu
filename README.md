<div align="center">

# NxEmu

**A free and open-source Nintendo Switch emulator written in C++**

[

![License](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)

](./license.txt)
[

![Website](https://img.shields.io/badge/Website-nxemu.com-0A66C2?style=for-the-badge)

](https://www.nxemu.com)
[

![Discord](https://img.shields.io/badge/Chat-Discord-5865F2?style=for-the-badge)

](https://discord.gg/hEa4hNyFWU)

[Website](https://www.nxemu.com) &nbsp;|&nbsp; [Downloads](https://www.nxemu.com/downloads.html) &nbsp;|&nbsp; [About](https://www.nxemu.com/about.html) &nbsp;|&nbsp; [Discord](https://discord.gg/hEa4hNyFWU)

</div>

---

## Overview

NxEmu is a Nintendo Switch emulator written in C++. It is developed in the open and licensed under the GNU General Public License v3.0.

## Platform Support

| Platform | Status               |
|----------|----------------------|
| Windows  | Supported            |
| macOS    | In development       |
| Android  | In development       |
| Linux    | In development       |

Support for macOS, Android, and Linux is under active development. These builds may be incomplete or unstable and are not yet recommended for general use.

## Download

Stable Windows releases are available on the [downloads page](https://www.nxemu.com/downloads.html).

## Building from Source

### Windows

**Requirements**

- Visual Studio with the "Desktop development with C++" workload
- Git

**Steps**

```bash
git clone --recursive https://github.com/N3xoX1/nxemu.git
cd nxemu
```

1. Open `nxemu.sln` in Visual Studio.
2. Select the **x64** configuration.
3. Build the solution.

If the repository was cloned without the `--recursive` flag, fetch the submodules with:

```bash
git submodule update --init --recursive
```

### macOS, Android, and Linux

Build instructions will be added as support for these platforms matures.

## Contributing

Contributions are welcome and appreciated.

1. Fork the repository and create a branch for your change.
2. Implement and test your changes.
3. Open a pull request describing what changed and why.

To report a bug or request a feature, please [open an issue](https://github.com/N3xoX1/nxemu/issues). For questions and general discussion, join the community on [Discord](https://discord.gg/hEa4hNyFWU).

## Legal Notice

NxEmu is an independent project and is not affiliated with, endorsed by, or sponsored by Nintendo. "Nintendo Switch" is a trademark of Nintendo Co., Ltd.

NxEmu does not include or distribute copyrighted games, firmware, or encryption keys. Users are responsible for obtaining these legally from hardware they own.

## License

NxEmu is licensed under the [GNU General Public License v3.0](./license.txt).