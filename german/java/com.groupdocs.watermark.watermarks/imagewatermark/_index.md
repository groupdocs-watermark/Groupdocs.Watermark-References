---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Bildwasserzeichen dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.watermark.watermarks/imagewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)

**All Implemented Interfaces:**
java.io.Closeable
```
public final class ImageWatermark extends Watermark implements Closeable
```

Stellt ein Bildwasserzeichen dar.

**Learn more:**

* [Adding image watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+image+watermarks)

Das folgende Beispiel zeigt, wie man ein Bildwasserzeichen zu einem Dokument beliebigen unterstützten Typs hinzufügt.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageWatermark(String filePath)](#ImageWatermark-java.lang.String-) | Initialisiert eine neue Instanz der `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)`‑Klasse mit einem angegebenen Dateipfad. |
|
|  | [ImageWatermark(InputStream stream)](#ImageWatermark-java.io.InputStream-) | Initialisiert eine neue Instanz der `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)`‑Klasse mit einem angegebenen Stream. |
|
| [ImageWatermark(System.IO.Stream stream)](#ImageWatermark-com.aspose.ms.System.IO.Stream-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getStream()](#getStream--) |  |
| [getTransparentImageContainer()](#getTransparentImageContainer--) |  |
| [getSize()](#getSize--) |  |
| [dispose()](#dispose--) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
|  | [close()](#close--) | Gibt die aktuelle Instanz frei. |
|
### ImageWatermark(String filePath) {#ImageWatermark-java.lang.String-}
```
public ImageWatermark(String filePath)
```


Initialisiert eine neue Instanz der `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)`‑Klasse mit einem angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zum Bild, das als Wasserzeichen verwendet wird. |
|

### ImageWatermark(InputStream stream) {#ImageWatermark-java.io.InputStream-}
```
public ImageWatermark(InputStream stream)
```


Initialisiert eine neue Instanz der `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)`‑Klasse mit einem angegebenen Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Stream, der das Bild enthält, das als Wasserzeichen verwendet wird. |
|

### ImageWatermark(System.IO.Stream stream) {#ImageWatermark-com.aspose.ms.System.IO.Stream-}
```
public ImageWatermark(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getTransparentImageContainer() {#getTransparentImageContainer--}
```
public final StreamContainer getTransparentImageContainer()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### dispose() {#dispose--}
```
public final void dispose()
```




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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
### close() {#close--}
```
public final void close()
```


Gibt die aktuelle Instanz frei.


