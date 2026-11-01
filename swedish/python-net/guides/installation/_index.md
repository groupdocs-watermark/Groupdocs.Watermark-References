---
title: "Installera GroupDocs.Watermark för Python via .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Installera GroupDocs.Watermark för Python via .NET på Windows, Linux eller macOS — från PyPI eller från ett förhandsnedladdat wheel, inklusive Intel‑ och Apple‑Silicon‑byggnader."
type: docs
url: /sv/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark för Python via .NET distribueras som ett förbyggt wheel på [PyPI](https://pypi.org/project/groupdocs-watermark-net/). PyPI-indexet innehåller ett separat wheel för varje stödjande plattform, och `pip` väljer automatiskt rätt. Varje wheel är självständigt: det paketerar den inbäddade runtime‑miljön och alla hanterade beroenden, så ingen Microsoft Office, OpenOffice eller separat runtime‑installation krävs.

Innan du installerar, granska [Systemkraven](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Wheeln kräver Linux med glibc 2.27 eller nyare, eller macOS 12 eller nyare, samt pip 20.3 eller nyare för installation. På Linux installerar du ICU, fontconfig, `libgdiplus` och Microsofts kärnfonter; på macOS installerar du `mono-libgdiplus` (se [Plattformsförutsättningar](#platform-prerequisites)).

## Install Package from PyPI

Öppna en terminal och kör installationskommandot för din plattform:

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

Efter att kommandot körts bör du se en utdata som liknar:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Wheel‑filnamnet kommer att innehålla ett platformsuffix som matchar ditt operativsystem — till exempel `manylinux_2_27_x86_64` på Linux, `macosx_12_0_arm64` på Apple Silicon, eller `win_amd64` på 64‑bit Windows.

## Add the Package to `requirements.txt`

För reproducerbara miljöer, lås paketversionen i din `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Installera sedan alla beroenden i ett steg:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Om din byggmiljö inte kan nå PyPI, ladda ner rätt wheel från [GroupDocs Releases‑webbplatsen](https://releases.groupdocs.com/watermark/python-net/) och installera den lokalt. Wheels publiceras för följande fyra plattformar:

| Plattform | Wheel‑filnamnet slutar med | Äldsta system |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Sedan version 26.10 anger filnamnen det äldsta system som varje wheel körs på, så pip 20.3 eller nyare avvisar en äldre version i förväg istället för att installera en runtime som inte kan starta. Wheels upp till 26.6 var märkta `manylinux1_x86_64`, `macosx_10_14_x86_64` och `macosx_11_0_arm64`.

Placera det nedladdade wheelt i din projektmapp och installera det sedan:

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

Ange wheel-filen explicit: PowerShell expanderar inte ett `*`-jokertecken för ett inbyggt kommando, så `pip install groupdocs_watermark_net-*.whl` misslyckas där.

Förväntad utdata (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

På Windows krävs inga extra steg. På Linux, installera ICU, fontconfig, `libgdiplus` och Microsofts kärnfonter; på macOS, `mono-libgdiplus`. Sidan [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) listar vilka funktioner som behöver var och en.

{{< tabs "platform-prereqs">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer finns i contrib-komponenten
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

Bekräfta att paketet importerades korrekt och kontrollera den installerade versionen:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Du kan också lista det installerade paketet med `pip show groupdocs-watermark-net` för att bekräfta versionen och platsen.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
