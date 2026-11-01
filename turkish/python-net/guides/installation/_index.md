---
title: "GroupDocs.Watermark for Python via .NET'i kurun"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET'i Windows, Linux veya macOS üzerinde — PyPI'dan ya da önceden indirilmiş bir wheel'dan, Intel ve Apple Silicon derlemeleri dahil olmak üzere kurun."
type: docs
url: /tr/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET, [PyPI](https://pypi.org/project/groupdocs-watermark-net/) üzerinde önceden derlenmiş bir wheel olarak dağıtılır. PyPI indeksi, her desteklenen platform için ayrı bir wheel barındırır ve `pip` otomatik olarak doğru olanı seçer. Her wheel bağımsızdır: gömülü çalışma zamanını ve tüm yönetilen bağımlılıkları paketler, bu yüzden Microsoft Office, OpenOffice veya ayrı bir çalışma zamanı kurulumu gerekmez.

Kurulumdan önce, [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) sayfasını inceleyin. Wheel'lar, Linux'ta glibc 2.27 veya daha yeni bir sürüm, macOS 12 veya daha yeni bir sürüm ve pip 20.3 veya daha yeni bir sürüm gerektirir. Linux'ta ICU, fontconfig, `libgdiplus` ve Microsoft core fontlarını; macOS'ta `mono-libgdiplus` kurun (bkz. [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Terminal açın ve platformunuz için kurulum komutunu çalıştırın:

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

Komutu çalıştırdıktan sonra benzer bir çıktı görmelisiniz:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Wheel dosya adı, işletim sisteminizle eşleşen bir platform soneki içerir — örneğin Linux'ta `manylinux_2_27_x86_64`, Apple Silicon'da `macosx_12_0_arm64` veya 64-bit Windows'ta `win_amd64`.

## Add the Package to `requirements.txt`

Tekrarlanabilir ortamlar için paket sürümünü `requirements.txt` dosyanıza sabitleyin:

```txt
groupdocs-watermark-net==26.10.0
```

Ardından tüm bağımlılıkları tek adımda kurun:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Derleme ortamınız PyPI'ye erişemiyorsa, uygun wheel'ı [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) adresinden indirip yerel olarak kurun. Wheel'lar aşağıdaki dört platform için yayınlanmıştır:

| Platform | Wheel dosya adı şu ile biter | En eski sistem |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10'dan itibaren dosya adları, her wheel'ın çalıştığı en eski sistemi gösterir, bu yüzden pip 20.3 veya daha yeni bir sürüm, daha eski bir wheel'ı yüklemeye çalışmadan önce reddeder. 26.6'ya kadar olan wheel'lar `manylinux1_x86_64`, `macosx_10_14_x86_64` ve `macosx_11_0_arm64` olarak etiketlenmişti.

İndirilen wheel dosyasını proje klasörünüze yerleştirin, ardından yükleyin:

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

Wheel dosyasını açıkça adlandırın: PowerShell, yerel bir komut için `*` joker karakterini genişletmez, bu yüzden `pip install groupdocs_watermark_net-*.whl` burada başarısız olur.

Beklenen çıktı (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Windows'ta ekstra bir adım gerekmez. Linux'ta ICU, fontconfig, `libgdiplus` ve Microsoft temel yazı tiplerini kurun; macOS'ta `mono-libgdiplus`. [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) sayfası hangi özelliklerin her birine ihtiyaç duyduğunu listeler.

{{< tabs "platform-prereqs">}}
{{< tab "Linux" >}}
```bash
# Debian: ttf-mscorefonts-installer, contrib bileşeninde bulunur
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

Paketin doğru içe aktarıldığını doğrulayın ve yüklü sürümü kontrol edin:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Sürümü ve konumu doğrulamak için `pip show groupdocs-watermark-net` komutuyla yüklü paketi listeleyebilirsiniz.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
