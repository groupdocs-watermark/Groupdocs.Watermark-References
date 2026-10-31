---
title: "فئة AddWatermarkResult"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل نتيجة إضافة علامات مائية إلى مستند."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/
is_root: false
weight: 10
---


## AddWatermarkResult class

يمثل نتيجة إضافة علامات مائية إلى مستند.

نوع AddWatermarkResult يعرض الأعضاء التالية:

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [number_applied_watermarks](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/number_applied_watermarks/) | عدد العلامات المائية المطبقة. |
| [succeeded](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/succeeded/) | قائمة العلامات المائية التي تم إنشاؤها حديثًا. |

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("sample_2_pages.pdf") as watermarker:
    font = gww.Font("Arial", 19.0, gww.FontStyle.BOLD | gww.FontStyle.ITALIC)
    watermark = gww.TextWatermark("Test watermark", font)

    watermark.foreground_color = gww.Color.red
    watermark.background_color = gww.Color.blue
    watermark.text_alignment = gww.TextAlignment.RIGHT
    watermark.opacity = 0.5

    result = watermarker.add(watermark)

    for item in result.succeeded:
        print("WatermarkId:", item.watermark_id)
        print("WatermarkType:", item.watermark_type)
        print("PageNumber:", item.page_number)
        print("WatermarkPosition:", item.watermark_position)

    watermarker.save("output.pdf")
```

### انظر أيضًا
* module [`groupdocs.watermark.watermarks.results`](/watermark/python-net/groupdocs.watermark.watermarks.results/)
