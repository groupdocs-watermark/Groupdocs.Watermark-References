---
title: "GroupDocs.Watermark for Python via .NET をインストールする"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "Windows、Linux、macOS 向けに GroupDocs.Watermark for Python via .NET をインストールします — PyPI からまたは事前にダウンロードした wheel から、Intel および Apple Silicon ビルドを含みます。"
type: docs
url: /ja/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET は [PyPI](https://pypi.org/project/groupdocs-watermark-net/) で事前構築された wheel として配布されています。PyPI インデックスはサポートされる各プラットフォーム向けに個別の wheel をホストし、`pip` が自動的に適切なものを選択します。各 wheel は自己完結型で、組み込みランタイムとすべてのマネージド依存関係をバンドルしているため、Microsoft Office、OpenOffice、別個のランタイムのインストールは不要です。

インストール前に、[System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) を確認してください。wheel を使用するには、glibc 2.27 以上の Linux、または macOS 12 以上、さらに pip 20.3 以上が必要です。Linux では ICU、fontconfig、`libgdiplus`、Microsoft のコアフォントをインストールし、macOS では `mono-libgdiplus` をインストールします（[Platform Prerequisites](#platform-prerequisites) を参照）。

## Install Package from PyPI

ターミナルを開き、使用しているプラットフォーム用のインストールコマンドを実行してください：

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

コマンドを実行すると、以下のような出力が表示されます：

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

The wheel ファイル名には、使用しているオペレーティングシステムに一致するプラットフォームサフィックスが含まれます — 例として Linux の `manylinux_2_27_x86_64`、Apple Silicon の `macosx_12_0_arm64`、または 64 ビット Windows の `win_amd64` が挙げられます。

## Add the Package to `requirements.txt`

再現可能な環境のために、`requirements.txt` にパッケージのバージョンを固定してください：

```txt
groupdocs-watermark-net==26.10.0
```

次に、すべての依存関係を一度にインストールします：

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

ビルド環境が PyPI にアクセスできない場合は、[GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) から適切な wheel をダウンロードし、ローカルにインストールしてください。wheel は以下の 4 つのプラットフォーム向けに公開されています：

| プラットフォーム | wheel ファイル名の末尾は | 最小サポートシステム |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27（Ubuntu 18.04、Debian 10、RHEL 8） |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10 以降、ファイル名には各 wheel が動作する最小システムが示されるようになり、pip 20.3 以降は起動できないランタイムをインストールしようとする代わりに、古い wheel を事前に拒否します。26.6 までの wheel は `manylinux1_x86_64`、`macosx_10_14_x86_64`、`macosx_11_0_arm64` とタグ付けされていました。

ダウンロードした wheel をプロジェクトフォルダーに置き、次にインストールしてください：

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

wheel ファイル名を明示的に指定してください：PowerShell はネイティブコマンドに対して `*` ワイルドカードを展開しないため、`pip install groupdocs_watermark_net-*.whl` は失敗します。

期待される出力（Linux）：

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Windows では追加の手順は不要です。Linux では ICU、fontconfig、`libgdiplus`、Microsoft のコアフォントをインストールしてください。macOS では `mono-libgdiplus` をインストールします。[System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) ページに各機能に必要なものが記載されています。

{{< tabs \"platform-prereqs\">}}
{{< tab "Linux" >}}
```bash
# Debian：ttf-mscorefonts-installer は contrib コンポーネントに含まれています
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

パッケージが正しくインポートされたことを確認し、インストールされたバージョンをチェックしてください：

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

`pip show groupdocs-watermark-net` でインストール済みパッケージを一覧表示し、バージョンと場所を確認することもできます。

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
