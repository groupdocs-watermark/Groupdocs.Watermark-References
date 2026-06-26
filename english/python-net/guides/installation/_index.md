---
title: Install GroupDocs.Watermark for Python via .NET
linkTitle: "Installation"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Install GroupDocs.Watermark for Python via .NET on Windows, Linux, or macOS — from PyPI or from a pre-downloaded wheel, including Intel and Apple Silicon builds."
type: docs
url: /python-net/guides/installation/
is_root: false
weight: 100
---


GroupDocs.Watermark for Python via .NET is distributed as a pre-built wheel on [PyPI](https://pypi.org/project/groupdocs-watermark-net/). The PyPI index hosts a separate wheel for each supported platform, and `pip` picks the correct one automatically. Each wheel is self-contained: it bundles the embedded runtime and every managed dependency, so no Microsoft Office, OpenOffice, or separate runtime install is required.

Before installing, confirm your environment matches the supported platforms and Python versions listed in the [System Requirements]() topic.

## Install Package from PyPI

Open a terminal and run the install command for your platform:

```ps
py -m pip install groupdocs-watermark-net
```

```bash
python3 -m pip install groupdocs-watermark-net
```

```bash
python3 -m pip install groupdocs-watermark-net
```

After running the command you should see output similar to:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.6.0-py3-none-win_amd64.whl (135.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 135.8/135.8 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.6.0
```

The wheel file name will include a platform suffix that matches your operating system — for example `manylinux1_x86_64` on Ubuntu/Debian, `macosx_11_0_arm64` on Apple Silicon, or `win_amd64` on 64-bit Windows.

## Add the Package to `requirements.txt`

For reproducible environments, pin the package version in your `requirements.txt`:

```txt
groupdocs-watermark-net==26.6.0
```

Then install all dependencies in one step:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

If your build environment cannot reach PyPI, download the appropriate wheel from the [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) and install it locally. Wheels are published for the following four platforms:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`

Place the downloaded wheel into your project folder, then install it:

```ps
py -m pip install ./groupdocs_watermark_net-26.6.0-py3-none-win_amd64.whl
```

```bash
python3 -m pip install ./groupdocs_watermark_net-26.6.0-py3-none-manylinux1_x86_64.whl
```

```bash
python3 -m pip install ./groupdocs_watermark_net-26.6.0-py3-none-macosx_10_14_x86_64.whl
```

```bash
python3 -m pip install ./groupdocs_watermark_net-26.6.0-py3-none-macosx_11_0_arm64.whl
```

Expected output:

```bash
Processing ./groupdocs_watermark_net-26.6.0-py3-none-*.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.6.0
```

## Platform Prerequisites

On Windows no extra steps are required. On Linux and macOS, install the native libraries the rendering engine depends on:

```bash
apt install libgdiplus libfontconfig1 libicu-dev ttf-mscorefonts-installer
```

```bash
brew install mono-libgdiplus
```

## Verify the Installation

Confirm the package imported correctly and check the installed version:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

You can also list the installed package with `pip show groupdocs-watermark-net` to confirm the version and location.

## Next Steps

- Follow the [Hello, World!]() guide to add your first watermark.
- Read the [Features Overview]() to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples]() to try every documented scenario locally.
