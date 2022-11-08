---
title: AsposeImageContainer
second_title: GroupDocs.Watermark for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.groupdocs.watermark.contents/asposeimagecontainer/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class AsposeImageContainer extends ContentPart
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeImageContainer(byte[] data)](#AsposeImageContainer-byte---) |  |
| [AsposeImageContainer(System.IO.Stream stream)](#AsposeImageContainer-com.aspose.ms.System.IO.Stream-) |  |
| [AsposeImageContainer(Image image)](#AsposeImageContainer-com.aspose.imaging.Image-) |  |
| [AsposeImageContainer(int width, int height)](#AsposeImageContainer-int-int-) |  |
| [AsposeImageContainer(String filePath)](#AsposeImageContainer-java.lang.String-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAsposeImage()](#getAsposeImage--) |  |
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
| [dispose()](#dispose--) | Disposes the current instance. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) |  |
| [getFileFormat(byte[] imageData)](#getFileFormat-byte---) |  |
| [checkWatermarkingLicenseRestrictions(Watermark watermark)](#checkWatermarkingLicenseRestrictions-com.groupdocs.watermark.Watermark-) |  |
| [save()](#save--) |  |
| [save(String filePath, boolean overwrite)](#save-java.lang.String-boolean-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) |  |
| [convert(ImageOptionsBase options)](#convert-com.aspose.imaging.ImageOptionsBase-) |  |
### AsposeImageContainer(byte[] data) {#AsposeImageContainer-byte---}
```
public AsposeImageContainer(byte[] data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

### AsposeImageContainer(System.IO.Stream stream) {#AsposeImageContainer-com.aspose.ms.System.IO.Stream-}
```
public AsposeImageContainer(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### AsposeImageContainer(Image image) {#AsposeImageContainer-com.aspose.imaging.Image-}
```
public AsposeImageContainer(Image image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.imaging.Image |  |

### AsposeImageContainer(int width, int height) {#AsposeImageContainer-int-int-}
```
public AsposeImageContainer(int width, int height)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### AsposeImageContainer(String filePath) {#AsposeImageContainer-java.lang.String-}
```
public AsposeImageContainer(String filePath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### getAsposeImage() {#getAsposeImage--}
```
public final Image getAsposeImage()
```




**Returns:**
com.aspose.imaging.Image
### getStreamContainer() {#getStreamContainer--}
```
public final StreamContainer getStreamContainer()
```




**Returns:**
com.groupdocs.watermark.internal.StreamContainer
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


Disposes the current instance.

### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
long
### getFileFormat(byte[] imageData) {#getFileFormat-byte---}
```
public static long getFileFormat(byte[] imageData)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageData | byte[] |  |

**Returns:**
long
### checkWatermarkingLicenseRestrictions(Watermark watermark) {#checkWatermarkingLicenseRestrictions-com.groupdocs.watermark.Watermark-}
```
public void checkWatermarkingLicenseRestrictions(Watermark watermark)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| overwrite | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### convert(ImageOptionsBase options) {#convert-com.aspose.imaging.ImageOptionsBase-}
```
public final AsposeImageContainer convert(ImageOptionsBase options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | com.aspose.imaging.ImageOptionsBase |  |

**Returns:**
[AsposeImageContainer](../../com.groupdocs.watermark.contents/asposeimagecontainer)
