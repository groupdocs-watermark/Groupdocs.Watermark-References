---
title: "Installieren Sie GroupDocs.Watermark für Python über .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Installieren Sie GroupDocs.Watermark für Python über .NET unter Windows, Linux oder macOS – von PyPI oder von einem vorab heruntergeladenen Wheel, einschließlich Intel‑ und Apple‑Silicon‑Builds."
type: docs
url: /de/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark für Python über .NET wird als vorgefertigtes Wheel auf [PyPI](https://pypi.org/project/groupdocs-watermark-net/) bereitgestellt. Der PyPI‑Index hostet ein separates Wheel für jede unterstützte Plattform, und `pip` wählt das richtige automatisch aus. Jedes Wheel ist eigenständig: es bündelt die eingebettete Laufzeit und alle verwalteten Abhängigkeiten, sodass keine Installation von Microsoft Office, OpenOffice oder einer separaten Laufzeit erforderlich ist.

Bevor Sie installieren, prüfen Sie die [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Die Wheels benötigen Linux mit glibc 2.27 oder neuer, oder macOS 12 oder neuer, sowie pip 20.3 oder neuer zur Installation. Unter Linux installieren Sie ICU, fontconfig, `libgdiplus` und die Microsoft‑Core‑Fonts; unter macOS installieren Sie `mono-libgdiplus` (siehe [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Öffnen Sie ein Terminal und führen Sie den Installationsbefehl für Ihre Plattform aus:

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

Nach dem Ausführen des Befehls sollten Sie eine ähnliche Ausgabe sehen:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Der Wheel‑Dateiname enthält ein Plattform‑Suffix, das Ihrem Betriebssystem entspricht – zum Beispiel `manylinux_2_27_x86_64` unter Linux, `macosx_12_0_arm64` auf Apple Silicon oder `win_amd64` unter 64‑Bit‑Windows.

## Add the Package to `requirements.txt`

Für reproduzierbare Umgebungen fixieren Sie die Paketversion in Ihrer `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Installieren Sie dann alle Abhängigkeiten in einem Schritt:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Wenn Ihre Build‑Umgebung PyPI nicht erreichen kann, laden Sie das passende Wheel von der [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) herunter und installieren es lokal. Wheels werden für die folgenden vier Plattformen veröffentlicht:

| Plattform | Wheel‑Dateiname endet mit | Ältestes System |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Seit 26.10 geben die Dateinamen das älteste System an, auf dem jedes Wheel läuft, sodass pip 20.3 oder neuer ein älteres sofort ablehnt, anstatt eine Laufzeit zu installieren, die nicht gestartet werden kann. Wheels bis 26.6 waren mit `manylinux1_x86_64`, `macosx_10_14_x86_64` und `macosx_11_0_arm64` gekennzeichnet.

Legen Sie das heruntergeladene Wheel in Ihren Projektordner und installieren Sie es dann:

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

Benennen Sie die Wheel-Datei explizit: PowerShell erweitert ein `*`-Wildcard für einen nativen Befehl nicht, sodass `pip install groupdocs_watermark_net-*.whl` dort fehlschlägt.

Erwartete Ausgabe (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Unter Windows sind keine zusätzlichen Schritte erforderlich. Unter Linux installieren Sie ICU, fontconfig, `libgdiplus` und die Microsoft Core Fonts; unter macOS `mono-libgdiplus`. Die Seite [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) listet auf, welche Funktionen jeweils benötigt werden.

{{< tabs \"platform-prereqs\">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf‑mscorefonts‑installer befindet sich in der contrib‑Komponente
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

Bestätigen Sie, dass das Paket korrekt importiert wurde, und prüfen Sie die installierte Version:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Sie können das installierte Paket auch mit `pip show groupdocs-watermark-net` auflisten, um Version und Speicherort zu bestätigen.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
