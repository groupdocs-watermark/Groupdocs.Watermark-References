---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر فئة أساسية مجردة لجزء من النص المنسق في المحتوى."
type: docs
weight: 26
url: /ar/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

يوفر فئة أساسية مجردة لجزء من النص المنسق في المحتوى.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
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
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


يحصل على نص الجزء.


**Returns:**
java.lang.String - نص الجزء.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


يحصل على خط النص.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


يحصل على لون المقدمة للنص.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


يحصل على لون الخلفية للنص.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

