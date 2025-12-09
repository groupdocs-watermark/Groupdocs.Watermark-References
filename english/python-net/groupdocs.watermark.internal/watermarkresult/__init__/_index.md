---
title: WatermarkResult constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes a new instance of the [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult) class.



```python
def __init__(self):
    ...
```




## __init__ {#int-System.TimeSpan-int-int}

Initializes a new instance of the [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult) class with specific values.



```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_document_size | int | The size of the source document in bytes. |
| processing_time | System.TimeSpan | The processing time in milliseconds. |
| final_document_size | int | The size of the final processed document in bytes. |
| number_watermarks_applied | int | The total number of watermarks applied to the document. |



### See Also
* module [`groupdocs.watermark.internal`](../../)
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult)
