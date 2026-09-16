# Python-DEB-Packages-for-Termux-3.11-3.14-
Python DEB Packages for Termux (3.11 – 3.14), STATIC versions. Build with docker.
# Python DEB Packages for Termux (3.11 – 3.14)

**Language:** [English](README.md) | [Русский](README.ru.md)

![Build](https://img.shields.io/badge/build-docker-blue)
![Platform](https://img.shields.io/badge/platform-termux-green)
![Arch](https://img.shields.io/badge/arch-aarch64%20%7C%20x86__64-lightgrey)
![Python](https://img.shields.io/badge/python-3.11%20%7C%203.12%20%7C%203.13%20%7C%203.14-yellow)

Ready-to-install `.deb` packages of Python for **Termux**.  
Built via Docker. Both regular and **static** builds are available.

---

## Contents

| Python version | Architecture    | Type    | Package                                    |
|----------------|-----------------|---------|--------------------------------------------|
| 3.11.10        | aarch64         | regular | `python-3.11_3.11.10_aarch64.deb`          |
| 3.11.10        | aarch64         | static  | `python-3.11-static_3.11.10_aarch64.deb`   |
| 3.11.10        | x86_64          | regular | `python-3.11_3.11.10_x86_64.deb`           |
| 3.11.10        | x86_64          | static  | `python-3.11-static_3.11.10_x86_64.deb`    |
| 3.12.12-1      | aarch64         | regular | `python-3.12_3.12.12-1_aarch64.deb`        |
| 3.12.12-1      | aarch64         | static  | `python-3.12-static_3.12.12-1_aarch64.deb` |
| 3.12.12-1      | x86_64          | regular | `python-3.12_3.12.12-1_x86_64.deb`         |
| 3.12.12-1      | x86_64          | static  | `python-3.12-static_3.12.12-1_x86_64.deb`  |
| 3.13.13        | aarch64         | regular | `python-3.13_3.13.13_aarch64.deb`          |
| 3.13.13        | aarch64         | static  | `python-3.13-static_3.13.13_aarch64.deb`   |
| 3.13.13        | x86_64          | regular | `python-3.13_3.13.13_x86_64.deb`           |
| 3.13.13        | x86_64          | static  | `python-3.13-static_3.13.13_x86_64.deb`    |
| 3.14.6         | aarch64         | regular | `python-3.14_3.14.6_aarch64.deb`           |
| 3.14.6         | aarch64         | static  | `python-3.14-static_3.14.6_aarch64.deb`    |
| 3.14.6         | x86_64          | regular | `python-3.14_3.14.6_x86_64.deb`            |
| 3.14.6         | x86_64          | static  | `python-3.14-static_3.14.6_x86_64.deb`     |

---

## Dependencies (`depends/`)

All required `.deb` packages for both `aarch64` and `x86_64` architectures.

### Compression and archive

| Package          | Version | Description                                |
|------------------|---------|--------------------------------------------|
| `brotli`         | 1.2.0   | Brotli compression library                 |
| `bzip2`          | 1.0.8-8 | High-quality block-sorting file compressor |
| `libbz2`         | 1.0.8-8 | Shared library for bzip2                   |
| `liblzma`        | 5.8.4   | XZ/LZMA compression library                |
| `liblzma-static` | 5.8.4   | Static build of liblzma                    |
| `xz-utils`       | 5.8.4   | XZ utilities (xz, unxz, xzcat)             |
| `zlib`           | 1.3.2   | zlib compression library                   |
| `zlib-static`    | 1.3.2   | Static build of zlib                       |
| `zstd`           | 1.5.7-1 | Zstandard compression                      |
| `pzstd`          | 1.5.7-1 | Parallel zstd                              |

### Crypto and certificates

| Package                | Version      | Description                         |
|------------------------|--------------|-------------------------------------|
| `openssl`              | 1:3.6.3      | TLS/SSL toolkit                     |
| `openssl-static`       | 1:3.6.3      | Static build of OpenSSL             |
| `openssl-tool`         | 1:3.6.3      | OpenSSL CLI tools                   |
| `ca-certificates`      | 1:2026.08.13 | Common CA certificates              |
| `ca-certificates-java` | 1:2026.08.13 | CA certificates for Java truststore |

### Core libraries

| Package                             | Version | Description                         |
|-------------------------------------|---------|-------------------------------------|
| `libandroid-support`                | 29-1    | Android compatibility shims         |
| `libandroid-support-static`         | 29-1    | Static build of libandroid-support  |
| `libandroid-posix-semaphore`        | 0.1-4   | POSIX semaphore support for Android |
| `libandroid-posix-semaphore-static` | 0.1-4   | Static build of posix-semaphore     |
| `libc++`                            | 29      | LLVM C++ standard library           |
| `libcrypt`                          | 0.2-6   | Password hashing library            |
| `libffi`                            | 3.8.0   | Foreign Function Interface          |
| `libffi-static`                     | 3.8.0   | Static build of libffi              |
| `libexpat`                          | 2.8.4   | XML parser library                  |
| `libexpat-static`                   | 2.8.4   | Static build of libexpat            |
| `gdbm`                              | 1.26-1  | GNU dbm database library            |
| `gdbm-static`                       | 1.26-1  | Static build of gdbm                |
| `libsqlite`                         | 3.53.4  | SQLite embedded database library    |
| `libsqlite-static`                  | 3.53.4  | Static build of libsqlite           |
| `libsqlite-tcl`                     | 3.53.4  | SQLite TCL bindings                 |
| `sqlite`                            | 3.53.4  | SQLite CLI                          |

### Terminal and text

| Package                  | Version                         | Description                        |
|--------------------------|---------------------------------|------------------------------------|
| `ncurses`                | 6.6.20260307+really6.5.20250830 | Terminal UI library                |
| `ncurses-static`         | 6.6.20260307+really6.5.20250830 | Static build of ncurses            |
| `ncurses-ui-libs`        | 6.6.20260307+really6.5.20250830 | ncurses UI libraries (panel, menu) |
| `ncurses-ui-libs-static` | 6.6.20260307+really6.5.20250830 | Static build of ncurses UI libs    |
| `ncurses-utils`          | 6.6.20260307+really6.5.20250830 | ncurses utilities (tic, infocmp)   |
| `readline`               | 8.3.3                           | GNU readline line-editing library  |
| `readline-static`        | 8.3.3                           | Static build of readline           |

### Graphics and fonts

| Package             | Version | Description               |
|---------------------|---------|---------------------------|
| `freetype`          | 2.14.3  | Font rendering engine     |
| `freetype-static`   | 2.14.3  | Static build of freetype  |
| `fontconfig`        | 2.18.3  | Font configuration library|
| `fontconfig-static` | 2.18.3  | Static build of fontconfig|
| `fontconfig-utils`  | 2.18.3  | Font management utilities |
| `libpng`            | 1.6.58  | PNG image library         |
| `libpng-static`     | 1.6.58  | Static build of libpng    |
| `ttf-dejavu`        | 2.37-8  | DejaVu TrueType fonts     |

### X11 (for tkinter)

| Package            | Version  | Description                     |
|--------------------|----------|---------------------------------|
| `libx11`           | 1.8.13-1 | X11 client library              |
| `libx11-static`    | 1.8.13-1 | Static build of libx11          |
| `libxau`           | 1.0.12-2 | X11 authorization library       |
| `libxcb`           | 1.17.0-1 | X11 C bindings                  |
| `libxcb-static`    | 1.17.0-1 | Static build of libxcb          |
| `libxdmcp`         | 1.1.5-2  | X Display Manager Control Proto |
| `libxdmcp-static`  | 1.1.5-2  | Static build of libxdmcp        |
| `libxext`          | 1.3.7    | X11 extensions                  |
| `libxext-static`   | 1.3.7    | Static build of libxext         |
| `libxft`           | 2.3.9-1  | X FreeType interface            |
| `libxft-static`    | 2.3.9-1  | Static build of libxft          |
| `libxrender`       | 0.9.12-1 | X Rendering extension           |
| `libxss`           | 1.2.5    | X Screen Saver extension        |
| `libxss-static`    | 1.2.5    | Static build of libxss          |
| `xcb-proto`        | 1.17.0-3 | XCB protocol descriptions       |
| `xorg-util-macros` | 1.20.2   | X.Org autotools macros          |
| `xorgproto`        | 2025.1   | X.Org protocol headers          |
| `xtrans`           | 1.6.0    | X transport library             |

### Scripting

| Package | Version  | Description     |
|---------|----------|-----------------|
| `tcl`   | 8.6.16   | Tcl interpreter |
| `tk`    | 8.6.14-1 | Tk toolkit      |
---

## Tested on

- Termux 0.119.0-beta.3 
- Devices: Pixel 10 Pro XL(emulator, x86-64, API 37.1) and iQOO 15R(real device, arm64-v8a, API 36)

---



## Disclaimer

Packages are provided **as is**. Installing third-party `.deb` files may conflict with official Termux packages (`python`, `python-pip`).

---

## License

Apache License 2.0 — see [LICENSE](LICENSE).

```
Copyright 2026 @propad810-prog

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
---

## Links

- [Termux Wiki](https://wiki.termux.com/)
- [Python Downloads](https://www.python.org/downloads/)
- [termux-packages](https://github.com/termux/termux-packages)

---

**Author:** @propad810-prog · **License:** MIT · **Last update:** 2026.09.16
