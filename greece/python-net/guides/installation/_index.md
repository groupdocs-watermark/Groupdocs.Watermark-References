---
title: "Εγκαταστήστε το GroupDocs.Watermark για Python μέσω .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Εγκαταστήστε το GroupDocs.Watermark για Python μέσω .NET σε Windows, Linux ή macOS — από το PyPI ή από προ-κατεβασμένο wheel, συμπεριλαμβανομένων των εκδόσεων για Intel και Apple Silicon."
type: docs
url: /el/python-net/guides/installation/
is_root: false
weight: 10
---


Το GroupDocs.Watermark για Python μέσω .NET διανέμεται ως προ-κατασκευασμένο wheel στο [PyPI](https://pypi.org/project/groupdocs-watermark-net/). Το ευρετήριο PyPI φιλοξενεί ξεχωριστό wheel για κάθε υποστηριζόμενη πλατφόρμα, και το `pip` επιλέγει αυτόματα το σωστό. Κάθε wheel είναι αυτόνομο: ενσωματώνει το ενσωματωμένο runtime και όλες τις διαχειριζόμενες εξαρτήσεις, ώστε να μην απαιτείται εγκατάσταση Microsoft Office, OpenOffice ή ξεχωριστής runtime.

Πριν την εγκατάσταση, ελέγξτε τις [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Τα wheels απαιτούν Linux με glibc 2.27 ή νεότερο, ή macOS 12 ή νεότερο, και pip 20.3 ή νεότερο για εγκατάσταση. Σε Linux, εγκαταστήστε ICU, fontconfig, `libgdiplus` και τις βασικές γραμματοσειρές της Microsoft· σε macOS, εγκαταστήστε `mono-libgdiplus` (δείτε [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Ανοίξτε ένα τερματικό και εκτελέστε την εντολή εγκατάστασης για την πλατφόρμα σας:

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

Μετά την εκτέλεση της εντολής θα πρέπει να δείτε έξοδο παρόμοια με:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Το όνομα του αρχείου wheel θα περιλαμβάνει ένα επίθημα πλατφόρμας που ταιριάζει με το λειτουργικό σας σύστημα — για παράδειγμα `manylinux_2_27_x86_64` σε Linux, `macosx_12_0_arm64` σε Apple Silicon ή `win_amd64` σε 64-bit Windows.

## Add the Package to `requirements.txt`

Για αναπαραγώγιμα περιβάλλοντα, κλειδώστε την έκδοση του πακέτου στο `requirements.txt`:

```txt
groupdocs-watermark-net==26.10.0
```

Στη συνέχεια εγκαταστήστε όλες τις εξαρτήσεις σε ένα βήμα:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Εάν το περιβάλλον κατασκευής σας δεν μπορεί να προσεγγίσει το PyPI, κατεβάστε το κατάλληλο wheel από την [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) και εγκαταστήστε το τοπικά. Τα wheels δημοσιεύονται για τις ακόλουθες τέσσερις πλατφόρμες:

| Πλατφόρμα | Το όνομα του αρχείου wheel λήγει με | Παλαιότερο σύστημα |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Από την έκδοση 26.10 τα ονόματα αρχείων δηλώνουν το παλαιότερο σύστημα στο οποίο τρέχει κάθε wheel, έτσι το pip 20.3 ή νεότερο απορρίπτει εκ των προτέρων ένα παλαιότερο αντί να εγκαταστήσει μια runtime που δεν μπορεί να ξεκινήσει. Τα wheels έως την έκδοση 26.6 είχαν ετικέτες `manylinux1_x86_64`, `macosx_10_14_x86_64` και `macosx_11_0_arm64`.

Τοποθετήστε το ληφθέν wheel στον φάκελο του έργου σας, στη συνέχεια εγκαταστήστε το:

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

Ονομάστε το αρχείο wheel ρητά: το PowerShell δεν επεκτείνει το σύμβολο μπαλαντέρ `*` για μια εγγενή εντολή, έτσι το `pip install groupdocs_watermark_net-*.whl` αποτυγχάνει εκεί.

Αναμενόμενη έξοδος (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Στα Windows δεν απαιτούνται επιπλέον βήματα. Στο Linux, εγκαταστήστε ICU, fontconfig, `libgdiplus` και τις βασικές γραμματοσειρές της Microsoft· στα macOS, `mono-libgdiplus`. Η σελίδα [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) αναφέρει ποιες λειτουργίες χρειάζονται το καθένα.

{{< tabs \"platform-prereqs\">}}
{{< tab \"Linux\" >}}
```bash
# Debian: το ttf-mscorefonts-installer βρίσκεται στο στοιχείο contrib
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

Επιβεβαιώστε ότι το πακέτο εισήχθη σωστά και ελέγξτε την εγκατεστημένη έκδοση:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Μπορείτε επίσης να εμφανίσετε το εγκατεστημένο πακέτο με `pip show groupdocs-watermark-net` για να επιβεβαιώσετε την έκδοση και τη θέση.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
