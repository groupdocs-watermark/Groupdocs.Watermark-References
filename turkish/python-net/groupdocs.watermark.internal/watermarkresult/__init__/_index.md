---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "WatermarkResult sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) sınıfı örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Belirli değerlerle yeni bir WatermarkResult örneği başlatır.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_document_size | `int` | Kaynak belgenin bayt cinsinden boyutu. |
| processing_time | `timedelta` | Milisaniye cinsinden işleme süresi. |
| final_document_size | `int` | Son işlenmiş belgenin boyutu bayt cinsindendir. |
| number_watermarks_applied | `int` | Belgeye uygulanan toplam filigran sayısı. |

### Ayrıca Bakınız
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
