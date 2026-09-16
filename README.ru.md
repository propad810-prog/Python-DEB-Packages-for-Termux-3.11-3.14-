# Python DEB пакеты для Termux (3.11 – 3.14)

**Язык:** [English](README.md) | [Русский](README.ru.md)

![Сборка](https://img.shields.io/badge/build-docker-blue)
![Платформа](https://img.shields.io/badge/platform-termux-green)
![Архитектура](https://img.shields.io/badge/arch-aarch64%20%7C%20x86__64-lightgrey)
![Python](https://img.shields.io/badge/python-3.11%20%7C%203.12%20%7C%203.13%20%7C%203.14-yellow)

Готовые к установке `.deb` пакеты Python для **Termux**.  
Собраны через Docker. Доступны как обычные, так и **статические** сборки.

---

## Содержание

| Версия Python | Архитектура | Тип      | Пакет                                      |
|---------------|-------------|----------|--------------------------------------------|
| 3.11.10       | aarch64     | обычный  | `python-3.11_3.11.10_aarch64.deb`          |
| 3.11.10       | aarch64     | статич.  | `python-3.11-static_3.11.10_aarch64.deb`   |
| 3.11.10       | x86_64      | обычный  | `python-3.11_3.11.10_x86_64.deb`           |
| 3.11.10       | x86_64      | статич.  | `python-3.11-static_3.11.10_x86_64.deb`    |
| 3.12.12-1     | aarch64     | обычный  | `python-3.12_3.12.12-1_aarch64.deb`        |
| 3.12.12-1     | aarch64     | статич.  | `python-3.12-static_3.12.12-1_aarch64.deb` |
| 3.12.12-1     | x86_64      | обычный  | `python-3.12_3.12.12-1_x86_64.deb`         |
| 3.12.12-1     | x86_64      | статич.  | `python-3.12-static_3.12.12-1_x86_64.deb`  |
| 3.13.13       | aarch64     | обычный  | `python-3.13_3.13.13_aarch64.deb`          |
| 3.13.13       | aarch64     | статич.  | `python-3.13-static_3.13.13_aarch64.deb`   |
| 3.13.13       | x86_64      | обычный  | `python-3.13_3.13.13_x86_64.deb`           |
| 3.13.13       | x86_64      | статич.  | `python-3.13-static_3.13.13_x86_64.deb`    |
| 3.14.6        | aarch64     | обычный  | `python-3.14_3.14.6_aarch64.deb`           |
| 3.14.6        | aarch64     | статич.  | `python-3.14-static_3.14.6_aarch64.deb`    |
| 3.14.6        | x86_64      | обычный  | `python-3.14_3.14.6_x86_64.deb`            |
| 3.14.6        | x86_64      | статич.  | `python-3.14-static_3.14.6_x86_64.deb`     |

---

## Зависимости (`depends/`)

Все необходимые `.deb` пакеты для архитектур `aarch64` и `x86_64`.

### Сжатие и архивация

| Пакет            | Версия  | Описание                                     |
|------------------|---------|----------------------------------------------|
| `brotli`         | 1.2.0   | Библиотека сжатия Brotli                     |
| `bzip2`          | 1.0.8-8 | Высококачественный блочный компрессор        |
| `libbz2`         | 1.0.8-8 | Разделяемая библиотека для bzip2             |
| `liblzma`        | 5.8.4   | Библиотека сжатия XZ/LZMA                    |
| `liblzma-static` | 5.8.4   | Статическая сборка liblzma                   |
| `xz-utils`       | 5.8.4   | Утилиты XZ (xz, unxz, xzcat)                 |
| `zlib`           | 1.3.2   | Библиотека сжатия zlib                       |
| `zlib-static`    | 1.3.2   | Статическая сборка zlib                      |
| `zstd`           | 1.5.7-1 | Сжатие Zstandard                             |
| `pzstd`          | 1.5.7-1 | Параллельный zstd                            |

### Криптография и сертификаты

| Пакет                  | Версия       | Описание                         |
|------------------------|--------------|----------------------------------|
| `openssl`              | 1:3.6.3      | Набор TLS/SSL                    |
| `openssl-static`       | 1:3.6.3      | Статическая сборка OpenSSL       |
| `openssl-tool`         | 1:3.6.3      | Консольные утилиты OpenSSL       |
| `ca-certificates`      | 1:2026.08.13 | Общие корневые сертификаты       |
| `ca-certificates-java` | 1:2026.08.13 | Сертификаты CA для Java          |

### Базовые библиотеки

| Пакет                               | Версия | Описание                            |
|-------------------------------------|--------|-------------------------------------|
| `libandroid-support`                | 29-1   | Прослойка совместимости с Android   |
| `libandroid-support-static`         | 29-1   | Статическая сборка libandroid-support|
| `libandroid-posix-semaphore`        | 0.1-4  | Поддержка POSIX семафоров в Android |
| `libandroid-posix-semaphore-static` | 0.1-4  | Статическая сборка posix-semaphore  |
| `libc++`                            | 29     | Стандартная библиотека C++ LLVM     |
| `libcrypt`                          | 0.2-6  | Библиотека хеширования паролей      |
| `libffi`                            | 3.8.0  | Интерфейс внешних функций           |
| `libffi-static`                     | 3.8.0  | Статическая сборка libffi           |
| `libexpat`                          | 2.8.4  | Библиотека разбора XML              |
| `libexpat-static`                   | 2.8.4  | Статическая сборка libexpat         |
| `gdbm`                              | 1.26-1 | Библиотека баз данных GNU dbm       |
| `gdbm-static`                       | 1.26-1 | Статическая сборка gdbm             |
| `libsqlite`                         | 3.53.4 | Встраиваемая БД SQLite              |
| `libsqlite-static`                  | 3.53.4 | Статическая сборка libsqlite        |
| `libsqlite-tcl`                     | 3.53.4 | Привязки SQLite к TCL               |
| `sqlite`                            | 3.53.4 | Консоль SQLite                      |

### Терминал и текст

| Пакет                    | Версия                          | Описание                             |
|--------------------------|---------------------------------|--------------------------------------|
| `ncurses`                | 6.6.20260307+really6.5.20250830 | Библиотека терминального интерфейса  |
| `ncurses-static`         | 6.6.20260307+really6.5.20250830 | Статическая сборка ncurses           |
| `ncurses-ui-libs`        | 6.6.20260307+really6.5.20250830 | UI-библиотеки ncurses (panel, menu)  |
| `ncurses-ui-libs-static` | 6.6.20260307+really6.5.20250830 | Статическая сборка UI-библиотек      |
| `ncurses-utils`          | 6.6.20260307+really6.5.20250830 | Утилиты ncurses (tic, infocmp)       |
| `readline`               | 8.3.3                           | Библиотека редактирования GNU readline|
| `readline-static`        | 8.3.3                           | Статическая сборка readline          |

### Графика и шрифты

| Пакет               | Версия | Описание                      |
|---------------------|--------|-------------------------------|
| `freetype`          | 2.14.3 | Движок рендеринга шрифтов     |
| `freetype-static`   | 2.14.3 | Статическая сборка freetype   |
| `fontconfig`        | 2.18.3 | Библиотека настройки шрифтов  |
| `fontconfig-static` | 2.18.3 | Статическая сборка fontconfig |
| `fontconfig-utils`  | 2.18.3 | Утилиты управления шрифтами   |
| `libpng`            | 1.6.58 | Библиотека изображений PNG    |
| `libpng-static`     | 1.6.58 | Статическая сборка libpng     |
| `ttf-dejavu`        | 2.37-8 | Шрифты DejaVu TrueType        |

### X11 (для tkinter)

| Пакет              | Версия   | Описание                         |
|--------------------|----------|----------------------------------|
| `libx11`           | 1.8.13-1 | Клиентская библиотека X11        |
| `libx11-static`    | 1.8.13-1 | Статическая сборка libx11        |
| `libxau`           | 1.0.12-2 | Библиотека авторизации X11       |
| `libxcb`           | 1.17.0-1 | Привязки X11 C                   |
| `libxcb-static`    | 1.17.0-1 | Статическая сборка libxcb        |
| `libxdmcp`         | 1.1.5-2  | Протокол управления X Display    |
| `libxdmcp-static`  | 1.1.5-2  | Статическая сборка libxdmcp      |
| `libxext`          | 1.3.7    | Расширения X11                   |
| `libxext-static`   | 1.3.7    | Статическая сборка libxext       |
| `libxft`           | 2.3.9-1  | Интерфейс X FreeType             |
| `libxft-static`    | 2.3.9-1  | Статическая сборка libxft        |
| `libxrender`       | 0.9.12-1 | Расширение рендеринга X          |
| `libxss`           | 1.2.5    | Расширение X Screen Saver        |
| `libxss-static`    | 1.2.5    | Статическая сборка libxss        |
| `xcb-proto`        | 1.17.0-3 | Описания протокола XCB           |
| `xorg-util-macros` | 1.20.2   | Макросы X.Org autotools          |
| `xorgproto`        | 2025.1   | Заголовки протоколов X.Org       |
| `xtrans`           | 1.6.0    | Библиотека транспорта X          |

### Скриптинг

| Пакет | Версия   | Описание          |
|-------|----------|-------------------|
| `tcl` | 8.6.16   | Интерпретатор Tcl |
| `tk`  | 8.6.14-1 | Набор Tk          |
---

## Проверено на

- Termux 0.119.0-beta.3
- Устройства: Pixel 10 Pro XL (эмулятор, x86-64, API 37.1) и iQOO 15R (реальное устройство, arm64-v8a, API 36)

---

## Отказ от ответственности

Пакеты предоставляются **как есть**. Установка сторонних `.deb` файлов может конфликтовать с официальными пакетами Termux (`python`, `python-pip`).

---

## Лицензия

Apache License 2.0 — см. [LICENSE](LICENSE).

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

## Ссылки

- [Termux Wiki](https://wiki.termux.com/)
- [Python Downloads](https://www.python.org/downloads/)
- [termux-packages](https://github.com/termux/termux-packages)

---

**Автор:** @propad810-prog · **Лицензия:** MIT · **Последнее обновление:** 2026.09.16
