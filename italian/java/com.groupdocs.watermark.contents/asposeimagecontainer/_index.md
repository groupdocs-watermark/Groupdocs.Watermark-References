---
title: "AsposeImageContainer"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: 
type: docs
weight: 10
url: /it/java/com.groupdocs.watermark.contents/asposeimagecontainer/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class AsposeImageContainer extends ContentPart
```

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [AsposeImageContainer(byte[] data)](#AsposeImageContainer-byte---) | <br /> |

|
|  | [AsposeImageContainer(System.IO.Stream stream)](#AsposeImageContainer-com.aspose.ms.System.IO.Stream-) | <br /> |

|
|  | [AsposeImageContainer(Image image)](#AsposeImageContainer-com.aspose.imaging.Image-) | <br /> |

|
|  | [AsposeImageContainer(int width, int height)](#AsposeImageContainer-int-int-) | <br /> |

|
|  | [AsposeImageContainer(String filePath)](#AsposeImageContainer-java.lang.String-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAsposeImage()](#getAsposeImage--) |  |
|  | [replaceImage(Image newImage)](#replaceImage-com.aspose.imaging.Image-) | <br /> |

|
| [getStreamContainer()](#getStreamContainer--) |  |
| [getAsTiffImage()](#getAsTiffImage--) |  |
| [getAsTiffFrame()](#getAsTiffFrame--) |  |
| [isTiffImage()](#isTiffImage--) |  |
| [isTiffFrame()](#isTiffFrame--) |  |
| [getAsGifImage()](#getAsGifImage--) |  |
| [isGifImage()](#isGifImage--) |  |
| [isJpegImage()](#isJpegImage--) |  |
| [isBmpImage()](#isBmpImage--) |  |
| [isEmfImage()](#isEmfImage--) |  |
| [getAsRasterImage()](#getAsRasterImage--) |  |
| [getWidth()](#getWidth--) |  |
| [getHeight()](#getHeight--) |  |
| [getDisposed()](#getDisposed--) |  |
|  | [dispose()](#dispose--) | Rilascia l'istanza corrente. |
|
|  | [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | <br /> |

|
| [getFileFormat(byte[] imageData)](#getFileFormat-byte---) |  |
|  | [checkWatermarkingLicenseRestrictions(Watermark watermark)](#checkWatermarkingLicenseRestrictions-com.groupdocs.watermark.Watermark-) | <br /> |

|
| [save()](#save--) |  |
| [save(String filePath, boolean overwrite)](#save-java.lang.String-boolean-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) |  |
| [convert(ImageOptionsBase options)](#convert-com.aspose.imaging.ImageOptionsBase-) |  |
### AsposeImageContainer(byte[] data) {#AsposeImageContainer-byte---}
```
public AsposeImageContainer(byte[] data)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] |  |

### AsposeImageContainer(System.IO.Stream stream) {#AsposeImageContainer-com.aspose.ms.System.IO.Stream-}
```
public AsposeImageContainer(System.IO.Stream stream)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### AsposeImageContainer(Image image) {#AsposeImageContainer-com.aspose.imaging.Image-}
```
public AsposeImageContainer(Image image)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | com.aspose.imaging.Image |  |

### AsposeImageContainer(int width, int height) {#AsposeImageContainer-int-int-}
```
public AsposeImageContainer(int width, int height)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int |  |
| altezza | int |  |

### AsposeImageContainer(String filePath) {#AsposeImageContainer-java.lang.String-}
```
public AsposeImageContainer(String filePath)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |

### getAsposeImage() {#getAsposeImage--}
```
public final Image getAsposeImage()
```




**Returns:**
com.aspose.imaging.Image
### replaceImage(Image newImage) {#replaceImage-com.aspose.imaging.Image-}
```
public final void replaceImage(Image newImage)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImage | com.aspose.imaging.Image |  |

### getStreamContainer() {#getStreamContainer--}
```
public final StreamContainer getStreamContainer()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getAsTiffImage() {#getAsTiffImage--}
```
public final TiffImage getAsTiffImage()
```




**Returns:**
com.aspose.imaging.fileformats.tiff.TiffImage
### getAsTiffFrame() {#getAsTiffFrame--}
```
public final TiffFrame getAsTiffFrame()
```




**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame
### isTiffImage() {#isTiffImage--}
```
public final boolean isTiffImage()
```




**Returns:**
boolean
### isTiffFrame() {#isTiffFrame--}
```
public final boolean isTiffFrame()
```




**Returns:**
boolean
### getAsGifImage() {#getAsGifImage--}
```
public final GifImage getAsGifImage()
```




**Returns:**
com.aspose.imaging.fileformats.gif.GifImage
### isGifImage() {#isGifImage--}
```
public final boolean isGifImage()
```




**Returns:**
boolean
### isJpegImage() {#isJpegImage--}
```
public final boolean isJpegImage()
```




**Returns:**
boolean
### isBmpImage() {#isBmpImage--}
```
public final boolean isBmpImage()
```




**Returns:**
boolean
### isEmfImage() {#isEmfImage--}
```
public final boolean isEmfImage()
```




**Returns:**
boolean
### getAsRasterImage() {#getAsRasterImage--}
```
public final RasterImage getAsRasterImage()
```




**Returns:**
com.aspose.imaging.RasterImage
### getWidth() {#getWidth--}
```
public final int getWidth()
```




**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```




**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```




**Returns:**
boolean
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.


### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
long
### getFileFormat(byte[] imageData) {#getFileFormat-byte---}
```
public static long getFileFormat(byte[] imageData)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageData | byte[] |  |

**Returns:**
long
### checkWatermarkingLicenseRestrictions(Watermark watermark) {#checkWatermarkingLicenseRestrictions-com.groupdocs.watermark.Watermark-}
```
public void checkWatermarkingLicenseRestrictions(Watermark watermark)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### save() {#save--}
```
public final void save()
```




### save(String filePath, boolean overwrite) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean overwrite)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |
| sovrascrivi | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### convert(ImageOptionsBase options) {#convert-com.aspose.imaging.ImageOptionsBase-}
```
public final AsposeImageContainer convert(ImageOptionsBase options)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| opzioni | com.aspose.imaging.ImageOptionsBase |  |

**Returns:**
[AsposeImageContainer](../../com.groupdocs.watermark.contents/asposeimagecontainer)
