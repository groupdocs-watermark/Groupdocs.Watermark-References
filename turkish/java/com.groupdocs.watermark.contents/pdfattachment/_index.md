---
title: "PdfAttachment"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF içeriğine eklenmiş bir dosyayı temsil eder."
type: docs
weight: 58
url: /tr/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

PDF içeriğine eklenmiş bir dosyayı temsil eder.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Ekli dosyanın adını alır. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ekli dosyanın adını ayarlar. |
|
|  | [getDescription()](#getDescription--) | Ekli dosyanın açıklamasını alır. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | Ekli dosyanın açıklamasını ayarlar. |
|
|  | [getContent()](#getContent--) | Ekli dosya içeriğini alır. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ekli dosya içeriğini ayarlar. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Ekli dosyanın adını alır.


**Returns:**
java.lang.String - Ekli dosyanın adı.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ekli dosyanın adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Ekli dosyanın adı. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Ekli dosyanın açıklamasını alır.


**Returns:**
java.lang.String - Ekli dosyanın açıklaması.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Ekli dosyanın açıklamasını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Ekli dosyanın açıklaması. |
|

### getContent() {#getContent--}
```
public byte[] getContent()
```


Ekli dosya içeriğini alır.


**Returns:**
byte[] - Ekli dosya içeriği.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ekli dosya içeriğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte[] | Ekli dosya içeriği. |
|

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Bir akıştan ekli dosyayı günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Ekli dosyadan bir akış alır.


**Returns:**
com.aspose.ms.System.IO.Stream
