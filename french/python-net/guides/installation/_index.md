---
title: "Installez GroupDocs.Watermark for Python via .NET"
linkTitle: "Installation"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Installez GroupDocs.Watermark for Python via .NET sur Windows, Linux ou macOS — depuis PyPI ou depuis une roue pré‑téléchargée, y compris les versions Intel et Apple Silicon."
type: docs
url: /fr/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET est distribué sous forme de roue pré‑construite sur [PyPI](https://pypi.org/project/groupdocs-watermark-net/). L’index PyPI héberge une roue distincte pour chaque plateforme prise en charge, et `pip` sélectionne automatiquement la bonne. Chaque roue est autonome : elle regroupe le runtime intégré et toutes les dépendances gérées, ainsi aucun Microsoft Office, OpenOffice ou installation de runtime séparé n’est requis.

Avant d’installer, consultez les [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). Les roues nécessitent Linux avec glibc 2.27 ou plus récent, ou macOS 12 ou plus récent, et pip 20.3 ou plus récent pour l’installation. Sous Linux, installez ICU, fontconfig, `libgdiplus` et les polices de base Microsoft ; sous macOS, installez `mono-libgdiplus` (voir [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

Ouvrez un terminal et exécutez la commande d’installation pour votre plateforme :

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

Après avoir exécuté la commande, vous devriez voir une sortie similaire à :

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

Le nom du fichier de la roue inclura un suffixe de plateforme correspondant à votre système d’exploitation — par exemple `manylinux_2_27_x86_64` sous Linux, `macosx_12_0_arm64` sur Apple Silicon, ou `win_amd64` sur Windows 64 bits.

## Add the Package to `requirements.txt`

Pour des environnements reproductibles, fixez la version du paquet dans votre `requirements.txt` :

```txt
groupdocs-watermark-net==26.10.0
```

Ensuite, installez toutes les dépendances en une seule étape :

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Si votre environnement de construction ne peut pas accéder à PyPI, téléchargez la roue appropriée depuis le [site des releases GroupDocs](https://releases.groupdocs.com/watermark/python-net/) et installez‑la localement. Les roues sont publiées pour les quatre plateformes suivantes :

| Plateforme | Le nom du fichier de la roue se termine par | Système le plus ancien |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Depuis la version 26.10, les noms de fichiers indiquent le système le plus ancien sur lequel chaque roue fonctionne, ainsi pip 20.3 ou plus récent refuse immédiatement une roue plus ancienne au lieu d’installer un runtime qui ne peut pas démarrer. Les roues jusqu’à la version 26.6 étaient étiquetées `manylinux1_x86_64`, `macosx_10_14_x86_64` et `macosx_11_0_arm64`.

Placez le fichier wheel téléchargé dans le dossier de votre projet, puis installez‑le :

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

Nommez explicitement le fichier wheel : PowerShell n’étend pas le caractère générique `*` pour une commande native, donc `pip install groupdocs_watermark_net-*.whl` échoue dans ce cas.

Sortie attendue (Linux) :

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Sur Windows, aucune étape supplémentaire n’est requise. Sur Linux, installez ICU, fontconfig, `libgdiplus` et les polices de base Microsoft ; sur macOS, `mono-libgdiplus`. La page [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) indique quelles fonctionnalités nécessitent chaque élément.

{{< tabs "platform-prereqs">}}
{{< tab "Linux" >}}
```bash
# Debian : ttf-mscorefonts-installer se trouve dans le composant contrib
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

Vérifiez que le paquet a été importé correctement et contrôlez la version installée :

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

Vous pouvez également lister le paquet installé avec `pip show groupdocs-watermark-net` pour confirmer la version et l’emplacement.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
