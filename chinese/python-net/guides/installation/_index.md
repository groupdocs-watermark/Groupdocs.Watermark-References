---
title: "安装 GroupDocs.Watermark for Python via .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "在 Windows、Linux 或 macOS 上安装 GroupDocs.Watermark for Python via .NET —— 可从 PyPI 或预下载的 wheel 安装，支持 Intel 和 Apple Silicon 架构。"
type: docs
url: /zh/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET 以预构建的 wheel 形式分发在 [PyPI](https://pypi.org/project/groupdocs-watermark-net/)。PyPI 索引为每个受支持的平台提供单独的 wheel，`pip` 会自动选择正确的版本。每个 wheel 都是自包含的：它捆绑了嵌入的运行时和所有托管依赖项，无需安装 Microsoft Office、OpenOffice 或其他运行时。

在安装之前，请查看 [系统要求](https://docs.groupdocs.com/watermark/python-net/system-requirements/)。这些 wheel 需要 Linux（glibc 2.27 或更高）或 macOS 12 及以上，并且需要 pip 20.3 或更高版本才能安装。在 Linux 上，需安装 ICU、fontconfig、`libgdiplus` 和 Microsoft 核心字体；在 macOS 上，需安装 `mono-libgdiplus`（参见 [平台先决条件](#platform-prerequisites)）。

## Install Package from PyPI

打开终端并运行适用于您平台的安装命令：

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

运行命令后，您应该会看到类似以下的输出：

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

wheel 文件名将包含与您的操作系统匹配的平台后缀——例如在 Linux 上为 `manylinux_2_27_x86_64`，在 Apple Silicon 上为 `macosx_12_0_arm64`，或在 64 位 Windows 上为 `win_amd64`。

## Add the Package to `requirements.txt`

为了实现可复现的环境，请在您的 `requirements.txt` 中固定包的版本：

```txt
groupdocs-watermark-net==26.10.0
```

然后一次性安装所有依赖：

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

如果您的构建环境无法访问 PyPI，请从 [GroupDocs Releases 网站](https://releases.groupdocs.com/watermark/python-net/) 下载相应的 wheel 并在本地安装。wheel 已针对以下四个平台发布：

| 平台 | wheel 文件名以以下结尾 | 最早支持的系统 |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27（Ubuntu 18.04，Debian 10，RHEL 8） |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

自 26.10 起，文件名会标明每个 wheel 所支持的最早系统，因此 pip 20.3 或更高版本会在安装前拒绝较旧的 wheel，而不是安装一个无法启动的运行时。至 26.6 版本的 wheel 使用标签 `manylinux1_x86_64`、`macosx_10_14_x86_64` 和 `macosx_11_0_arm64`。

将下载的 wheel 放入项目文件夹，然后安装它：

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

明确指定 wheel 文件名：PowerShell 不会为本机命令展开 `*` 通配符，因此 `pip install groupdocs_watermark_net-*.whl` 会在此处失败。

预期输出（Linux）：

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

在 Windows 上无需额外步骤。 在 Linux 上，安装 ICU、fontconfig、`libgdiplus` 和 Microsoft 核心字体；在 macOS 上，安装 `mono-libgdiplus`。[系统要求](https://docs.groupdocs.com/watermark/python-net/system-requirements/) 页面列出了每项功能所需的组件。

{{< tabs \"platform-prereqs\">}}
{{< tab "Linux" >}}
```bash
# Debian：ttf-mscorefonts-installer 位于 contrib 组件中
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

确认包已正确导入并检查已安装的版本：

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

您也可以使用 `pip show groupdocs-watermark-net` 列出已安装的包，以确认版本和位置。

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
