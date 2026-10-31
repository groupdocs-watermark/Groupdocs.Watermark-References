---
title: "تثبيت GroupDocs.Watermark for Python via .NET"
linkTitle: "Installation"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "تثبيت GroupDocs.Watermark for Python via .NET على Windows أو Linux أو macOS — من PyPI أو من wheel تم تنزيله مسبقًا، بما في ذلك إصدارات Intel و Apple Silicon."
type: docs
url: /ar/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET موزع كـ wheel مُسبق البناء على [PyPI](https://pypi.org/project/groupdocs-watermark-net/). يحتوي فهرس PyPI على wheel منفصل لكل منصة مدعومة، ويختار `pip` المناسب تلقائيًا. كل wheel مستقل: يجمع وقت التشغيل المضمن وكل الاعتماديات المدارة، لذا لا يلزم تثبيت Microsoft Office أو OpenOffice أو أي بيئة تشغيل منفصلة.

قبل التثبيت، راجع [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/). تحتاج الـ wheels إلى Linux مع glibc 2.27 أو أحدث، أو macOS 12 أو أحدث، و pip 20.3 أو أحدث للتثبيت. على Linux، ثبّت ICU و fontconfig و `libgdiplus` وخطوط Microsoft الأساسية؛ على macOS، ثبّت `mono-libgdiplus` (انظر [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

افتح طرفية ونفّذ أمر التثبيت لمنصتك:

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

بعد تشغيل الأمر يجب أن ترى مخرجات مشابهة لـ:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

اسم ملف الـ wheel سيتضمن لاحقة منصة تتطابق مع نظام تشغيلك — على سبيل المثال `manylinux_2_27_x86_64` على Linux، `macosx_12_0_arm64` على Apple Silicon، أو `win_amd64` على Windows 64‑bit.

## Add the Package to `requirements.txt`

لضمان بيئات قابلة لإعادة الإنتاج، قم بتثبيت نسخة الحزمة في ملف `requirements.txt` الخاص بك:

```txt
groupdocs-watermark-net==26.10.0
```

ثم قم بتثبيت جميع الاعتماديات خطوة واحدة:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

إذا لم يتمكن بيئة البناء الخاصة بك من الوصول إلى PyPI، قم بتنزيل الـ wheel المناسب من [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) ثم ثبّته محليًا. يتم نشر الـ wheels للمنصات الأربعة التالية:

| المنصة | اسم ملف الـ wheel ينتهي بـ | أقدم نظام |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

منذ الإصدار 26.10، تُظهر أسماء الملفات أقدم نظام تشغيل يمكن للـ wheel تشغيله، لذا يرفض pip 20.3 أو أحدث الـ wheel الأقدم مسبقًا بدلاً من تثبيت بيئة تشغيل لا يمكن تشغيلها. الـ wheels حتى الإصدار 26.6 كانت مُعلمة بـ `manylinux1_x86_64`، `macosx_10_14_x86_64` و `macosx_11_0_arm64`.

ضع ملف الـ wheel الذي تم تنزيله في مجلد المشروع الخاص بك، ثم قم بتثبيته:

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

قم بتسمية ملف الـ wheel صراحةً: لا يقوم PowerShell بتوسيع حرف البدل `*` لأمر أصلي، لذا فإن `pip install groupdocs_watermark_net-*.whl` يفشل هناك.

المخرجات المتوقعة (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

في Windows لا تحتاج إلى خطوات إضافية. في Linux، قم بتثبيت ICU و fontconfig و `libgdiplus` وخطوط Microsoft الأساسية؛ في macOS، `mono-libgdiplus`. صفحة [متطلبات النظام](https://docs.groupdocs.com/watermark/python-net/system-requirements/) تسرد الميزات التي تحتاج كل منها.

{{< tabs "platform-prereqs">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer موجود في مكوّن contrib
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

تأكد من استيراد الحزمة بشكل صحيح وتحقق من الإصدار المثبت:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

يمكنك أيضًا سرد الحزمة المثبتة باستخدام `pip show groupdocs-watermark-net` لتأكيد الإصدار والموقع.

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
