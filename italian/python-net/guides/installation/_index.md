---
title: "Installa GroupDocs.Watermark per Python via .NET"
linkTitle: "Installation"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Installa GroupDocs.Watermark per Python via .NET su Windows, Linux o macOS — da PyPI o da una wheel pre‑scaricata, incluse le versioni per Intel e Apple Silicon."
type: docs
url: /it/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark per Python via .NET è distribuito come wheel pre‑costruita su [PyPI](https://pypi.org/project/groupdocs-watermark-net/). L'indice PyPI ospita una wheel separata per ogni piattaforma supportata, e `pip` seleziona automaticamente quella corretta. Ogni wheel è auto‑contenuta: raggruppa il runtime incorporato e tutte le dipendenze gestite, quindi non è necessario installare Microsoft Office, OpenOffice o un runtime separato.

Prima di installare, controlla i [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Le wheel richiedono Linux con glibc 2.27 o superiore, o macOS 12 o superiore, e pip 20.3 o superiore per l'installazione. Su Linux, installa ICU, fontconfig, `libgdiplus` e i font core di Microsoft; su macOS, installa `mono-libgdiplus` (vedi [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Apre un terminale ed esegui il comando di installazione per la tua piattaforma:

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

Dopo aver eseguito il comando dovresti vedere un output simile a:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Il nome del file wheel includerà un suffisso di piattaforma che corrisponde al tuo sistema operativo — ad esempio `manylinux_2_27_x86_64` su Linux, `macosx_12_0_arm64` su Apple Silicon, o `win_amd64` su Windows a 64 bit.

## Add the Package to `requirements.txt`

Per ambienti riproducibili, fissa la versione del pacchetto nel tuo `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Quindi installa tutte le dipendenze in un unico passaggio:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Se il tuo ambiente di compilazione non può raggiungere PyPI, scarica la wheel appropriata dal [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) e installala localmente. Le wheel sono pubblicate per le seguenti quattro piattaforme:

| Piattaforma | Il nome del file wheel termina con | Sistema più vecchio |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

A partire da 26.10 i nomi dei file indicano il sistema più vecchio su cui ogni wheel può essere eseguita, quindi pip 20.3 o versioni successive rifiuta una wheel più vecchia fin da subito invece di installare un runtime che non può avviarsi. Le wheel fino alla 26.6 erano etichettate `manylinux1_x86_64`, `macosx_10_14_x86_64` e `macosx_11_0_arm64`.

Posiziona il file wheel scaricato nella cartella del tuo progetto, quindi installalo:

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

Specifica esplicitamente il nome del file wheel: PowerShell non espande il carattere jolly `*` per un comando nativo, quindi `pip install groupdocs_watermark_net-*.whl` fallisce.

Output previsto (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Su Windows non sono necessari passaggi aggiuntivi. Su Linux, installa ICU, fontconfig, `libgdiplus` e i font di base Microsoft; su macOS, `mono-libgdiplus`. La pagina [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) elenca quali funzionalità richiedono ciascuno.

{{< tabs "platform-prereqs">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer è nel componente contrib
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

Conferma che il pacchetto sia stato importato correttamente e verifica la versione installata:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Puoi anche elencare il pacchetto installato con `pip show groupdocs-watermark-net` per confermare la versione e la posizione.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
