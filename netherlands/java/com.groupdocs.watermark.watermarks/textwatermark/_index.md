---
title: "TextWatermark"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een tekstwatermerk voor."
type: docs
weight: 18
url: /nl/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Stelt een tekstwatermerk voor.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Het volgende voorbeeld toont hoe de tekstwatermerk geschaald kan worden afhankelijk van de grootte van de bovenliggende container.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermark.setSizingType(SizingType.ScaleToParentDimensions);
>    watermark.setRotateAngle(45);
>    watermark.setScaleFactor(0.4);
>
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Initialiseert een nieuw exemplaar van de `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` klasse met een opgegeven tekst en een lettertype. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Haalt de tekst op die als watermerk wordt gebruikt. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst in die als watermerk wordt gebruikt. |
|
|  | [getFont()](#getFont--) | Haalt het lettertype van de tekst op. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Stelt het lettertype van de tekst in. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Haalt de voorgrondkleur van de tekst op. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Stelt de voorgrondkleur van de tekst in. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Haalt de achtergrondkleur van de tekst op. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Stelt de achtergrondkleur van de tekst in. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Haalt het watermerk `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` op. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Stelt het watermerk `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` in. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Haalt de opvulinstellingen van deze `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` op. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Stelt de opvulinstellingen van deze `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` in. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Initialiseert een nieuw exemplaar van de `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` klasse met een opgegeven tekst en een lettertype.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | De tekst die als watermerk wordt gebruikt. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|

### getText() {#getText--}
```
public final String getText()
```


Haalt de tekst op die als watermerk wordt gebruikt.


**Returns:**
java.lang.String - De string die de watermerktekst vertegenwoordigt.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Stelt de tekst in die als watermerk wordt gebruikt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De string die de watermerktekst vertegenwoordigt. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Haalt het lettertype van de tekst op.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Stelt het lettertype van de tekst in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Het lettertype van de tekst. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Haalt de voorgrondkleur van de tekst op.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Stelt de voorgrondkleur van de tekst in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | De voorgrondkleur van de tekst. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Haalt de achtergrondkleur van de tekst op.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Stelt de achtergrondkleur van de tekst in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | De achtergrondkleur van de tekst. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Haalt het watermerk `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` op.

Standaardwaarde is `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - Het watermerk `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Stelt het watermerk `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` in.

Standaardwaarde is `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | Het watermerk `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getForegroundColorConsideringOpacity() {#getForegroundColorConsideringOpacity--}
```
public final Color getForegroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getBackgroundColorConsideringOpacity() {#getBackgroundColorConsideringOpacity--}
```
public final Color getBackgroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getPadding() {#getPadding--}
```
public final Thickness getPadding()
```


Haalt de opvulinstellingen van deze `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` op. Deze eigenschap is alleen van toepassing op afbeeldingsbestanden.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Stelt de opvulinstellingen van deze `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` in. Deze eigenschap is alleen van toepassing op afbeeldingsbestanden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | De opvulinstellingen van deze `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|

### deepClone() {#deepClone--}
```
public Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
