---
title: "ImageWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una filigrana immagine."
type: docs
weight: 13
url: /it/java/com.groupdocs.watermark.watermarks/imagewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)

**All Implemented Interfaces:**
java.io.Closeable
```
public final class ImageWatermark extends Watermark implements Closeable
```

Rappresenta una filigrana immagine.

**Learn more:**

* [Adding image watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+image+watermarks)

Il seguente esempio dimostra come aggiungere una filigrana immagine a un documento di qualsiasi tipo supportato.
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageWatermark(String filePath)](#ImageWatermark-java.lang.String-) | Inizializza una nuova istanza della classe `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` con un percorso file specificato. |
|
|  | [ImageWatermark(InputStream stream)](#ImageWatermark-java.io.InputStream-) | Inizializza una nuova istanza della classe `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` con uno stream specificato. |
|
| [ImageWatermark(System.IO.Stream stream)](#ImageWatermark-com.aspose.ms.System.IO.Stream-) |  |
## Metodi

| Metodo | Descrizione |
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
|  | [close()](#close--) | Rilascia l'istanza corrente. |
|
### ImageWatermark(String filePath) {#ImageWatermark-java.lang.String-}
```
public ImageWatermark(String filePath)
```


Inizializza una nuova istanza della classe `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` con un percorso file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso dell'immagine che verrà utilizzata come filigrana. |
|

### ImageWatermark(InputStream stream) {#ImageWatermark-java.io.InputStream-}
```
public ImageWatermark(InputStream stream)
```


Inizializza una nuova istanza della classe `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` con uno stream specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Lo stream contenente l'immagine che verrà utilizzata come filigrana. |
|

### ImageWatermark(System.IO.Stream stream) {#ImageWatermark-com.aspose.ms.System.IO.Stream-}
```
public ImageWatermark(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
### close() {#close--}
```
public final void close()
```


Rilascia l'istanza corrente.


