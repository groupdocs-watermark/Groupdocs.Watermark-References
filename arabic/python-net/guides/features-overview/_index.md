---
title: "نظرة عامة على الميزات"
linkTitle: "Features overview"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "GroupDocs.Watermark للبايثون عبر .NET يضيف، يبحث، ويزيل العلامات المائية النصية والصورية من خلال واجهة برمجة تطبيقات واحدة مستقلة عن التنسيق — مع وضع خاص بالتنسيق، تحرير شجرة المحتوى، القفل، والتصوير النقطي."
type: docs
url: /ar/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark للبايثون عبر .NET يضيف، يبحث، ويزيل العلامات المائية عبر مجموعة واسعة من [تنسيقات المستندات المدعومة](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). كل عملية تتبع نفس سير العمل: افتح مستندًا باستخدام [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)، استدعِ `add()` أو `search()` أو `remove()`، ثم `save()` النتيجة مرة أخرى إلى تنسيقها الأصلي. يمكن دمج القدرات أدناه بحرية في تمريرة واحدة.

## Text and image watermarks

أضف علامات مائية نصية أو صورية منسقة مع تحكم كامل في الخط، اللون، الشفافية، الدوران، المحاذاة، والحجم. يمكن تحميل العلامات الصورية من ملف أو تدفق. راجع [Add text watermarks](/watermark/python-net/guides/add-text/) و[Add image watermarks](/watermark/python-net/guides/add-image/).

## Customization and tiling

حدد موضع العلامة المائية باستخدام إحداثيات مطلقة أو محاذاة نسبية إلى العنصر الأب وهوامش، قم بتكبيرها نسبة إلى الصفحة، دوّرها، وكرّرها عبر الصفحة بأكملها بنمط متكرر. راجع [Customize watermarks](/watermark/python-net/guides/customize/)، [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)، و[Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

ضع العلامات المائية باستخدام الخيارات التي تناسب كل تنسيق — عناصر PDF، التعليقات التوضيحية، وتعليقات الطباعة فقط؛ شرائح العروض التقديمية، القوالب، التخطيطات، والملاحظات؛ أوراق عمل الجداول، الخلفيات، والرؤوس/التذييلات؛ صفحات Visio؛ وأقسام Word والصفحات المقفلة. راجع [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) والمواضيع الأخرى للتنسيقات في [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

ابحث عن العلامات المائية الموجودة بالفعل في مستند — بما في ذلك تلك التي أضافتها أدوات الطرف الثالث — بالنص الدقيق، التعبير النمطي، تشابه الصورة، أو تنسيق النص، وادمج المعايير باستخدام `and_`/`or_`/`not_`. بمجرد العثور عليها، استبدل نصها أو صورتها، أو أزلها. راجع [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)، [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/)، و[Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` يكشف شجرة محتوى مخصصة للتنسيق بحيث يمكنك فحص وتعديل الأشكال الموجودة، كائنات/قطع/تعليقات PDF، المرفقات، الخلفيات، والرؤوس/التذييلات — ويمكنك إضافة علامة مائية إلى الصور المضمنة داخل المستند باستخدام `get_images()`. راجع [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

اجعل العلامات المائية صعبة الإزالة عن طريق قفلها، حماية مستندات Word، إضافة تعليقات PDF للطباعة فقط، أو تحويل صفحات PDF إلى رسومات raster بحيث لا يمكن تحرير العلامة المائية. راجع [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) و [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

اقرأ نوع ملف المستند، عدد الصفحات، وحجمه دون تعديلها، وقم بسرد جميع صيغ الملفات التي تدعمها المكتبة. راجع [Get document info](/watermark/python-net/guides/get-document-info/) و [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark for Python via .NET يعمل بالكامل على بنيتك التحتية الخاصة — لا تغادر مستنداتك بيئتك. الحزمة عبارة عن wheel مستقل يجمع كل ما يحتاجه، لذا لا يلزم تثبيت Microsoft Office أو OpenOffice أو أي بيئة تشغيل منفصلة. راجع [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) للمنصات المدعومة والاعتمادات الأصلية.
