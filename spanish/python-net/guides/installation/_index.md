---
title: "Instala GroupDocs.Watermark para Python a través de .NET"
linkTitle: "Installation"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Instala GroupDocs.Watermark para Python a través de .NET en Windows, Linux o macOS — desde PyPI o desde una rueda pre‑descargada, incluidas compilaciones para Intel y Apple Silicon."
type: docs
url: /es/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark para Python a través de .NET se distribuye como una rueda preconstruida en [PyPI](https://pypi.org/project/groupdocs-watermark-net/). El índice de PyPI aloja una rueda separada para cada plataforma compatible, y `pip` selecciona la correcta automáticamente. Cada rueda es auto‑contenida: incluye el tiempo de ejecución incrustado y todas las dependencias gestionadas, por lo que no se requiere instalar Microsoft Office, OpenOffice o un tiempo de ejecución separado.

Antes de instalar, revisa los [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Las ruedas requieren Linux con glibc 2.27 o superior, o macOS 12 o superior, y pip 20.3 o superior para instalar. En Linux, instala ICU, fontconfig, `libgdiplus` y las fuentes centrales de Microsoft; en macOS, instala `mono-libgdiplus` (ver [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Abre una terminal y ejecuta el comando de instalación para tu plataforma:

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

Después de ejecutar el comando deberías ver una salida similar a:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

El nombre del archivo de la rueda incluirá un sufijo de plataforma que coincida con tu sistema operativo — por ejemplo `manylinux_2_27_x86_64` en Linux, `macosx_12_0_arm64` en Apple Silicon, o `win_amd64` en Windows de 64 bits.

## Add the Package to `requirements.txt`

Para entornos reproducibles, fija la versión del paquete en tu `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Luego instala todas las dependencias en un solo paso:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Si tu entorno de compilación no puede acceder a PyPI, descarga la rueda apropiada desde el [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) e instálala localmente. Las ruedas se publican para las siguientes cuatro plataformas:

| Plataforma | El nombre del archivo de la rueda termina con | Sistema más antiguo |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Desde la versión 26.10 los nombres de archivo indican el sistema más antiguo en el que cada rueda funciona, por lo que pip 20.3 o superior rechaza una más antigua de antemano en lugar de instalar un tiempo de ejecución que no pueda iniciarse. Las ruedas hasta la 26.6 estaban etiquetadas `manylinux1_x86_64`, `macosx_10_14_x86_64` y `macosx_11_0_arm64`.

Coloque el wheel descargado en la carpeta de su proyecto, luego instálelo:

{{< tabs \"install-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install .\groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< /tabs >}}

Nombre el archivo wheel explícitamente: PowerShell no expande el comodín `*` para un comando nativo, por lo que `pip install groupdocs_watermark_net-*.whl` falla allí.

Salida esperada (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

En Windows no se requieren pasos adicionales. En Linux, instale ICU, fontconfig, `libgdiplus` y las fuentes principales de Microsoft; en macOS, `mono-libgdiplus`. La página de [Requisitos del sistema](https://docs.groupdocs.com/watermark/python-net/system-requirements/) enumera qué características necesita cada uno.

{{< tabs \"platform-prereqs\">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer está en el componente contrib
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

Confirme que el paquete se importó correctamente y verifique la versión instalada:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

También puede listar el paquete instalado con `pip show groupdocs-watermark-net` para confirmar la versión y la ubicación.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
