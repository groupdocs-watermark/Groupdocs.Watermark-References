---
title: "Instal GroupDocs.Watermark untuk Python via .NET"
linkTitle: "Installation"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Instal GroupDocs.Watermark untuk Python via .NET di Windows, Linux, atau macOS — dari PyPI atau dari wheel yang sudah diunduh sebelumnya, termasuk build Intel dan Apple Silicon."
type: docs
url: /id/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark untuk Python via .NET didistribusikan sebagai wheel pra-bangun di [PyPI](https://pypi.org/project/groupdocs-watermark-net/). Indeks PyPI menyediakan wheel terpisah untuk setiap platform yang didukung, dan `pip` memilih yang tepat secara otomatis. Setiap wheel bersifat mandiri: ia menggabungkan runtime tersemat dan semua dependensi yang dikelola, sehingga tidak diperlukan instalasi Microsoft Office, OpenOffice, atau runtime terpisah.

Sebelum Anda menginstal, tinjau [Persyaratan Sistem](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Wheel memerlukan Linux dengan glibc 2.27 atau lebih baru, atau macOS 12 atau lebih baru, serta pip 20.3 atau lebih baru untuk instalasi. Di Linux, instal ICU, fontconfig, `libgdiplus` dan font inti Microsoft; di macOS, instal `mono-libgdiplus` (lihat [Prasyarat Platform](#platform-prerequisites)).

## Install Package from PyPI

Buka terminal dan jalankan perintah instalasi untuk platform Anda:

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

Setelah menjalankan perintah Anda akan melihat output serupa dengan:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Nama file wheel akan menyertakan akhiran platform yang cocok dengan sistem operasi Anda — misalnya `manylinux_2_27_x86_64` di Linux, `macosx_12_0_arm64` di Apple Silicon, atau `win_amd64` di Windows 64-bit.

## Add the Package to `requirements.txt`

Untuk lingkungan yang dapat direproduksi, tentukan versi paket di `requirements.txt` Anda:

```txt
groupdocs-watermark-net==26.10.0
```

Kemudian instal semua dependensi dalam satu langkah:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Jika lingkungan build Anda tidak dapat mengakses PyPI, unduh wheel yang sesuai dari [situs rilis GroupDocs](https://releases.groupdocs.com/watermark/python-net/) dan instal secara lokal. Wheel dipublikasikan untuk empat platform berikut:

| Platform | Nama file wheel berakhiran | Sistem tertua |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Sejak 26.10 nama file menyatakan sistem tertua yang dapat dijalankan setiap wheel, sehingga pip 20.3 atau lebih baru menolak yang lebih lama di awal alih-alih menginstal runtime yang tidak dapat dijalankan. Wheel hingga 26.6 ditandai `manylinux1_x86_64`, `macosx_10_14_x86_64` dan `macosx_11_0_arm64`.

Letakkan wheel yang diunduh ke dalam folder proyek Anda, lalu instal:

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

Berikan nama file wheel secara eksplisit: PowerShell tidak memperluas wildcard `*` untuk perintah native, sehingga `pip install groupdocs_watermark_net-*.whl` gagal di sana.

Output yang diharapkan (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Di Windows tidak diperlukan langkah tambahan. Di Linux, instal ICU, fontconfig, `libgdiplus`, dan font inti Microsoft; di macOS, `mono-libgdiplus`. Halaman [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) mencantumkan fitur mana yang memerlukan masing‑masing.

{{< tabs "platform-prereqs">}}
{{< tab "Linux" >}}
```bash
# Debian: ttf-mscorefonts-installer berada di komponen contrib
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

Konfirmasi paket diimpor dengan benar dan periksa versi yang terinstal:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Anda juga dapat menampilkan paket yang terinstal dengan `pip show groupdocs-watermark-net` untuk mengonfirmasi versi dan lokasinya.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
