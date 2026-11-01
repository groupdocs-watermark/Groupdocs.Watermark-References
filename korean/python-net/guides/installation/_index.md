---
title: "GroupDocs.Watermark for Python via .NET 설치"
linkTitle: "Installation"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "Windows, Linux 또는 macOS에서 GroupDocs.Watermark for Python via .NET를 설치합니다 — PyPI 또는 사전 다운로드된 휠에서, Intel 및 Apple Silicon 빌드를 포함합니다."
type: docs
url: /ko/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET는 [PyPI](https://pypi.org/project/groupdocs-watermark-net/)에서 사전 구축된 휠로 배포됩니다. PyPI 인덱스는 각 지원 플랫폼마다 별도의 휠을 호스팅하며, `pip`가 자동으로 올바른 휠을 선택합니다. 각 휠은 자체 포함형으로, 포함된 런타임과 모든 관리 종속성을 번들링하므로 Microsoft Office, OpenOffice 또는 별도 런타임 설치가 필요하지 않습니다.

설치하기 전에 [시스템 요구 사항](https://docs.groupdocs.com/watermark/python-net/system-requirements/)을 검토하십시오. 휠은 glibc 2.27 이상이 설치된 Linux 또는 macOS 12 이상이 필요하며, pip 20.3 이상이어야 설치할 수 있습니다. Linux에서는 ICU, fontconfig, `libgdiplus` 및 Microsoft core fonts를 설치하고, macOS에서는 `mono-libgdiplus`를 설치하십시오 ( [플랫폼 전제 조건](#platform-prerequisites) 참조).

## Install Package from PyPI

터미널을 열고 해당 플랫폼에 맞는 설치 명령을 실행하십시오:

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

명령을 실행한 후 다음과 유사한 출력이 표시됩니다:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

The wheel 파일 이름에는 운영 체제와 일치하는 플랫폼 접미사가 포함됩니다 — 예를 들어 Linux에서는 `manylinux_2_27_x86_64`, Apple Silicon에서는 `macosx_12_0_arm64`, 64비트 Windows에서는 `win_amd64`.

## Add the Package to `requirements.txt`

재현 가능한 환경을 위해 `requirements.txt`에 패키지 버전을 고정하세요:

```txt
groupdocs-watermark-net==26.10.0
```

그런 다음 모든 종속성을 한 번에 설치합니다:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

빌드 환경에서 PyPI에 접근할 수 없는 경우, [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/)에서 적절한 wheel을 다운로드하고 로컬에 설치하십시오. wheel은 다음 네 가지 플랫폼에 대해 제공됩니다:

| 플랫폼 | Wheel 파일 이름은 다음으로 끝납니다 | 가장 오래된 시스템 |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10부터 파일 이름에 각 wheel이 실행되는 가장 오래된 시스템이 명시되므로, pip 20.3 이상에서는 오래된 wheel을 앞서 거부하고 실행할 수 없는 런타임을 설치하지 않습니다. 26.6까지의 wheel은 `manylinux1_x86_64`, `macosx_10_14_x86_64` 및 `macosx_11_0_arm64`로 태그되었습니다.

다운로드한 wheel을 프로젝트 폴더에 넣은 다음 설치하십시오:

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

wheel 파일 이름을 명시적으로 지정하십시오: PowerShell은 네이티브 명령에 대해 `*` 와일드카드를 확장하지 않으므로 `pip install groupdocs_watermark_net-*.whl`이 여기서 실패합니다.

예상 출력 (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Windows에서는 추가 단계가 필요하지 않습니다. Linux에서는 ICU, fontconfig, `libgdiplus` 및 Microsoft core fonts를 설치하고; macOS에서는 `mono-libgdiplus`를 설치합니다. [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) 페이지에 각 기능에 필요한 항목이 나열되어 있습니다.

{{< tabs \"platform-prereqs\">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer는 contrib 구성 요소에 포함되어 있습니다
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

패키지가 올바르게 가져와졌는지 확인하고 설치된 버전을 확인하십시오:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

`pip show groupdocs-watermark-net` 명령으로 설치된 패키지를 나열하여 버전과 위치를 확인할 수 있습니다.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
