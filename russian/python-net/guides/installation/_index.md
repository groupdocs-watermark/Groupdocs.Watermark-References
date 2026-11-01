---
title: "Установите GroupDocs.Watermark для Python через .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Установите GroupDocs.Watermark для Python через .NET на Windows, Linux или macOS — из PyPI или из предварительно загруженного wheel, включая сборки для Intel и Apple Silicon."
type: docs
url: /ru/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark для Python через .NET распространяется как предварительно собранный wheel на [PyPI](https://pypi.org/project/groupdocs-watermark-net/). Индекс PyPI содержит отдельный wheel для каждой поддерживаемой платформы, и `pip` автоматически выбирает правильный. Каждый wheel автономен: он включает встроенный runtime и все управляемые зависимости, поэтому установка Microsoft Office, OpenOffice или отдельного runtime не требуется.

Перед установкой ознакомьтесь с [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Для wheel требуется Linux с glibc 2.27 или новее, либо macOS 12 или новее, а также pip 20.3 или новее. На Linux установите ICU, fontconfig, `libgdiplus` и шрифты Microsoft core fonts; на macOS установите `mono-libgdiplus` (см. [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Откройте терминал и выполните команду установки для вашей платформы:

{{< tabs \"install-pypi\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< /tabs >}}

После выполнения команды вы должны увидеть вывод, похожий на:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Имя файла wheel будет включать суффикс платформы, соответствующий вашей операционной системе — например `manylinux_2_27_x86_64` на Linux, `macosx_12_0_arm64` на Apple Silicon или `win_amd64` на 64‑битном Windows.

## Add the Package to `requirements.txt`

Для воспроизводимых окружений зафиксируйте версию пакета в вашем `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Затем установите все зависимости одной командой:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Если ваша среда сборки не может достичь PyPI, загрузите соответствующий wheel с [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) и установите его локально. Wheels публикуются для следующих четырёх платформ:

| Платформа | Имя файла wheel заканчивается на | Самая старая система |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Начиная с версии 26.10 имена файлов указывают самую старую систему, на которой работает каждый wheel, поэтому pip 20.3 или новее отклоняет более старый wheel сразу, вместо установки runtime, который не может запуститься. Wheels до версии 26.6 были помечены `manylinux1_x86_64`, `macosx_10_14_x86_64` и `macosx_11_0_arm64`.

Поместите загруженный wheel в папку вашего проекта, затем установите его:

{{< tabs "install-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install .\groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< /tabs >}}

Укажите имя wheel‑файла явно: PowerShell не расширяет подстановочный символ `*` для нативной команды, поэтому `pip install groupdocs_watermark_net-*.whl` там не работает.

Ожидаемый вывод (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

В Windows дополнительные шаги не требуются. В Linux установите ICU, fontconfig, `libgdiplus` и основные шрифты Microsoft; в macOS — `mono-libgdiplus`. Страница [Системные требования](https://docs.groupdocs.com/watermark/python-net/system-requirements/) перечисляет, какие функции требуют каждый из компонентов.

{{< tabs "platform-prereqs">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer находится в компоненте contrib
sudo sed -i '/^Components:/s/main/main contrib/' /etc/apt/sources.list.d/debian.sources
sudo apt-get update
sudo apt-get install -y libicu-dev libfontconfig1 libgdiplus ttf-mscorefonts-installer
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
brew install mono-libgdiplus
```
{{< /tab >}}
{{< /tabs >}}

## Verify the Installation

Подтвердите, что пакет импортирован корректно, и проверьте установленную версию:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Вы также можете вывести список установленного пакета с помощью `pip show groupdocs-watermark-net`, чтобы подтвердить версию и местоположение.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
