---
title: "Класс AddWatermarkResult"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет результат добавления водяных знаков в документ."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/
is_root: false
weight: 10
---


## AddWatermarkResult class

Представляет результат добавления водяных знаков в документ.

Тип AddWatermarkResult раскрывает следующие члены:

### Свойства
| Свойство | Описание |
| :- | :- |
| [number_applied_watermarks](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/number_applied_watermarks/) | Количество применённых водяных знаков. |
| [succeeded](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/succeeded/) | Список недавно созданных водяных знаков. |

### Пример

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

### См. также
* module [`groupdocs.watermark.watermarks.results`](/watermark/python-net/groupdocs.watermark.watermarks.results/)
