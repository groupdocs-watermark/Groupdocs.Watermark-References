---
title: "Installeer GroupDocs.Watermark voor Python via .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Installeer GroupDocs.Watermark voor Python via .NET op Windows, Linux of macOS — vanaf PyPI of vanaf een vooraf gedownloade wheel, inclusief builds voor Intel en Apple Silicon."
type: docs
url: /nl/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark voor Python via .NET wordt gedistribueerd als een vooraf gebouwde wheel op [PyPI](https://pypi.org/project/groupdocs-watermark-net/). De PyPI‑index hostt een aparte wheel voor elk ondersteund platform, en `pip` kiest automatisch de juiste. Elke wheel is zelfstandig: hij bundelt de ingebedde runtime en alle beheerde afhankelijkheden, zodat er geen Microsoft Office, OpenOffice of aparte runtime‑installatie nodig is.

Voordat u installeert, bekijk de [Systeemvereisten](https://docs.groupdocs.com/watermark/python-net/system-requirements/). De wheels hebben Linux met glibc 2.27 of nieuwer, of macOS 12 of nieuwer, en pip 20.3 of nieuwer nodig om te installeren. Op Linux installeert u ICU, fontconfig, `libgdiplus` en de Microsoft‑kernlettertypen; op macOS installeert u `mono-libgdiplus` (zie [Platformvereisten](#platform-prerequisites)).

## Install Package from PyPI

Open een terminal en voer het installatie‑commando voor uw platform uit:

{{< tabs "install-pypi">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< /tabs >}}

Na het uitvoeren van het commando zou u output moeten zien die lijkt op:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

De bestandsnaam van de wheel bevat een platformsuffix die overeenkomt met uw besturingssysteem — bijvoorbeeld `manylinux_2_27_x86_64` op Linux, `macosx_12_0_arm64` op Apple Silicon, of `win_amd64` op 64‑bit Windows.

## Add the Package to `requirements.txt`

Voor reproduceerbare omgevingen, zet de pakketversie vast in uw `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Installeer vervolgens alle afhankelijkheden in één stap:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Als uw build‑omgeving geen toegang heeft tot PyPI, download dan de juiste wheel van de [GroupDocs Releases‑website](https://releases.groupdocs.com/watermark/python-net/) en installeer deze lokaal. Wheels worden gepubliceerd voor de volgende vier platforms:

| Platform | Wheel‑bestandsnaam eindigt op | Oudste systeem |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Sinds 26.10 geven de bestandsnamen het oudste systeem aan waarop elke wheel draait, zodat pip 20.3 of nieuwer een oudere versie direct weigert in plaats van een runtime te installeren die niet kan starten. Wheels tot 26.6 waren getagd `manylinux1_x86_64`, `macosx_10_14_x86_64` en `macosx_11_0_arm64`.

Plaats het gedownloade wheel in uw projectmap en installeer het vervolgens:

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

Noem het wheel‑bestand expliciet: PowerShell breidt een `*`‑wildcard niet uit voor een native opdracht, waardoor `pip install groupdocs_watermark_net-*.whl` daar faalt.

Verwachte output (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Op Windows zijn geen extra stappen vereist. Op Linux installeert u ICU, fontconfig, `libgdiplus` en de Microsoft core‑fonts; op macOS `mono-libgdiplus`. De [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) pagina geeft aan welke functies elk van deze nodig hebben.

{{< tabs "platform-prereqs">}}
{{< tab "Linux" >}}
```bash
# Debian: ttf-mscorefonts-installer bevindt zich in de contrib‑component
sudo sed -i '/^Components:/s/main/main contrib/' /etc/apt/sources.list.d/debian.sources
sudo apt-get update
sudo apt-get install -y libicu-dev libfontconfig1 libgdiplus ttf-mscorefonts-installer
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
brew install mono-libgdiplus
```
{{< /tab >}}
{{< /tabs >}}

## Verify the Installation

Bevestig dat het pakket correct is geïmporteerd en controleer de geïnstalleerde versie:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

U kunt het geïnstalleerde pakket ook weergeven met `pip show groupdocs-watermark-net` om de versie en locatie te bevestigen.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
