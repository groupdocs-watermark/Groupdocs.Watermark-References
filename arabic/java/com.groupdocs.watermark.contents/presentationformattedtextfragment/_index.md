---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل جزءًا من النص المنسق في مستند PowerPoint."
type: docs
weight: 82
url: /ar/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

يمثل جزءًا من النص المنسق في مستند PowerPoint.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحصل على نص الجزء. |
|
|  | [getFont()](#getFont--) | يحصل على خط النص. |
|
|  | [getForegroundColor()](#getForegroundColor--) | يحصل على لون المقدمة للنص. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية للنص. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | يحصل على الارتباط التشعبي المرتبط بالنص. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | يضبط الارتباط التشعبي المرتبط بالنص. |
|
### getText() {#getText--}
```
public String getText()
```


يحصل على نص الجزء.


**Returns:**
java.lang.String - نص الجزء.

### getFont() {#getFont--}
```
public Font getFont()
```


يحصل على خط النص.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


يحصل على لون المقدمة للنص.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الخلفية للنص.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


يحصل على الارتباط التشعبي المرتبط بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | actionType | int | الإجراء الذي يفعّل الارتباط التشعبي. |
|

**Returns:**
java.lang.String - عنوان URL للارتباط التشعبي الذي يتم تفعيله عند الإجراء المحدد.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


يضبط الارتباط التشعبي المرتبط بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | actionType | int | الإجراء الذي يفعّل الارتباط التشعبي. |
|
|  | عنوان URL | java.lang.String | عنوان URL للارتباط التشعبي. |
|

