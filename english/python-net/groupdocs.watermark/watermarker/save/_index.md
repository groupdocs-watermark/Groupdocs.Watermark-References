---
title: save method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 70
---

## save {#}

Saves the document data to the underlying stream.



```python
def save(self):
    ...
```



### Example 


Remove particular text fragments from the email message body/subject and save the email message.


## save {#str}

Saves the document to the specified file location.



```python
def save(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path to save the document data to. |

### Example 


Add the watermark and save the document to another file.


## save {#io.RawIOBase}

Saves the document to the specified stream.



```python
def save(self, document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The stream to save the document data to. |

### Example 


Add watermark and save the document to the memory stream.


## save {#groupdocs.watermark.options.SaveOptions}

Saves the document data to the underlying stream using save options.



```python
def save(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | groupdocs.watermark.options.SaveOptions | Additional options to use when saving a document. |

### Example 


Add watermark and save the document with default [`SaveOptions`](/watermark/python-net/groupdocs.watermark.options/saveoptions).


## save {#str-groupdocs.watermark.options.SaveOptions}

Saves the document to the specified file location using save options.



```python
def save(self, file_path, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path to save the document data to. |
| options | groupdocs.watermark.options.SaveOptions | Additional options to use when saving a document. |

### Example 


Add the watermark and save the document to another file with default [`SaveOptions`](/watermark/python-net/groupdocs.watermark.options/saveoptions).


## save {#io.RawIOBase-groupdocs.watermark.options.SaveOptions}

Saves the document to the specified stream using save options.



```python
def save(self, document, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The stream to save the document data to. |
| options | groupdocs.watermark.options.SaveOptions | Additional options to use when saving a document. |

### Example 


Add watermark and save the document to the memory stream with default [`SaveOptions`](/watermark/python-net/groupdocs.watermark.options/saveoptions).



### See Also
* module [`groupdocs.watermark`](../../)
* class [`SaveOptions`](/watermark/python-net/groupdocs.watermark.options/saveoptions)
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
