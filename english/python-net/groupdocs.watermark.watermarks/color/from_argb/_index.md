---
title: from_argb method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 30
---

## from_argb {#int}

Creates a [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) structure from a 32-bit ARGB value.


### Returns 


The [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) structure that this method creates.


```python
def from_argb(self, argb):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| argb | int | A value specifying the 32-bit ARGB value. |


## from_argb {#int-groupdocs.watermark.watermarks.Color}

Creates a [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) structure from the specified [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) structure, 
but with the new specified alpha value.


### Returns 


The [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) that this method creates.


```python
def from_argb(self, alpha, base_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | int | The alpha value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
| base_color | [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) | The [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) from which to create the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentOutOfRangeException | Alpha is less than 0 or greater than 255. |




## from_argb {#int-int-int}

Creates a [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) structure from the specified 8-bit color values (red, green, and blue) and
the alpha value is implicitly 255 (fully opaque).


### Returns 


The [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) that this method creates.


```python
def from_argb(self, red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| red | int | The red component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
| green | int | The green component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
| blue | int | The blue component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentOutOfRangeException | Red, green, or blue is less than 0 or greater than 255. |




## from_argb {#int-int-int-int}

Creates a [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) structure from the four ARGB component  (alpha, red, green, and blue) values.


### Returns 


The [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color) that this method creates.


```python
def from_argb(self, alpha, red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | int | The alpha component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
| red | int | The red component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
| green | int | The green component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
| blue | int | The blue component value for the new [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color). Valid values are 0 through 255. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentOutOfRangeException | Red, green, or blue is less than 0 or greater than 255. |





### See Also
* module [`groupdocs.watermark.watermarks`](../../)
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color)
