---
title: create_watermarker method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/create_watermarker/
is_root: false
weight: 20
---

## create_watermarker {#}

Loads a content from the attached file.


### Returns 


The instance of appropriate descendant of [`Content`](/watermark/python-net/groupdocs.watermark.contents/content) class.


```python
def create_watermarker(self):
    ...
```




## create_watermarker {#groupdocs.watermark.options.LoadOptions}

Loads a content from the attached file with the specified load options.


### Returns 


The instance of appropriate descendant of [`Content`](/watermark/python-net/groupdocs.watermark.contents/content) class.


```python
def create_watermarker(self, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | groupdocs.watermark.options.LoadOptions | Additional options to use when loading an attachment content. |


## create_watermarker {#groupdocs.watermark.options.LoadOptions-groupdocs.watermark.WatermarkerSettings}

Loads a content from the attached file with the specified load options and settings.


### Returns 


The instance of appropriate descendant of [`Content`](/watermark/python-net/groupdocs.watermark.contents/content) class.


```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | groupdocs.watermark.options.LoadOptions | Additional options to use when loading an attachment content. |
| watermarker_settings | [`WatermarkerSettings`](/watermark/python-net/groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |



### See Also
* module [`groupdocs.watermark.contents.spreadsheet`](../../)
* class [`Content`](/watermark/python-net/groupdocs.watermark.contents/content)
* class [`SpreadsheetAttachment`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment)
