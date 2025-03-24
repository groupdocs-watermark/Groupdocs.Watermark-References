---
title: Watermarker constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---

## __init__ {#str}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified document path.



```python
def __init__(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path to load the document from. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Load and save a content of any supported format.


## __init__ {#io.RawIOBase}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream.



```python
def __init__(self, document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The stream to load document from. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Load and save a document of any supported format.


## __init__ {#str-groupdocs.watermark.options.LoadOptions}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified
document path and load options.



```python
def __init__(self, file_path, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path to load document from. |
| options | groupdocs.watermark.options.LoadOptions | Additional options to use when loading a document. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Load encrypted PDF document using password.


## __init__ {#str-groupdocs.watermark.WatermarkerSettings}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified
document path and settings.



```python
def __init__(self, file_path, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path to load document from. |
| settings | [`WatermarkerSettings`](/watermark/python-net/groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Set searchable objects globally (for all documents that will be loaded after that).


## __init__ {#io.RawIOBase-groupdocs.watermark.options.LoadOptions}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream
and load options.



```python
def __init__(self, document, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The stream to load document from. |
| options | groupdocs.watermark.options.LoadOptions | Additional options to use when loading a document. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Load encrypted PDF document using password


## __init__ {#io.RawIOBase-groupdocs.watermark.WatermarkerSettings}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream
and settings.



```python
def __init__(self, document, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The stream to load document from. |
| settings | [`WatermarkerSettings`](/watermark/python-net/groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Set searchable objects globally (for all documents that will be loaded after that).


## __init__ {#str-groupdocs.watermark.options.LoadOptions-groupdocs.watermark.WatermarkerSettings}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified
document path, load options and settings.



```python
def __init__(self, file_path, options, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path to load document from. |
| options | groupdocs.watermark.options.LoadOptions | Additional options to use when loading a document. |
| settings | [`WatermarkerSettings`](/watermark/python-net/groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Find particular text fragments in email message body/subject.


## __init__ {#io.RawIOBase-groupdocs.watermark.options.LoadOptions-groupdocs.watermark.WatermarkerSettings}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker) class with the specified stream,
load options and settings.



```python
def __init__(self, document, options, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The stream to load document from. |
| options | groupdocs.watermark.options.LoadOptions | Additional options to use when loading a document. |
| settings | [`WatermarkerSettings`](/watermark/python-net/groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |



### Example 


Find particular text fragments in email message body/subject.



### See Also
* module [`groupdocs.watermark`](../../)
* class [`InvalidPasswordException`](/watermark/python-net/groupdocs.watermark.exceptions/invalidpasswordexception)
* class [`UnsupportedFileTypeException`](/watermark/python-net/groupdocs.watermark.exceptions/unsupportedfiletypeexception)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
