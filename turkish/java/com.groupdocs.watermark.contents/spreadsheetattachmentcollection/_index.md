---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesindeki eklerin bir koleksiyonunu temsil eder."
type: docs
weight: 102
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Excel belgesindeki eklerin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)` türündeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Bir ek, `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` öğesine eklenir. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Bir bağlantı aracılığıyla ek ekler (belge ekli dosya içeriğini içermez). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Bir ek, `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` öğesine eklenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileContent | byte[] | Eklenecek dosyanın içeriği. |
|
|  | sourceFullName | java.lang.String | Ekli dosyanın tam adı (Uzantı, dosyayı açmak için uygun uygulamayı belirlemek için kullanılır). |
|
|  | previewImageContent | byte[] | Ekli dosyanın önizleme görüntüsü bayt dizisi olarak. |
|
|  | x | double | Ek çerçevesinin x-koordinatı (puan cinsinden). |
|
|  | y | double | Ek çerçevesinin y-koordinatı (puan cinsinden). |
|
|  | width | double | Eklenti çerçevesinin nokta cinsinden genişliği. |
|
|  | height | double | Eklenti çerçevesinin nokta cinsinden yüksekliği. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Bir bağlantı aracılığıyla ek ekler (belge ekli dosya içeriğini içermez).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Bağlantılı dosyanın yolu. |
|
|  | previewImageContent | byte[] | Ekli dosyanın önizleme görüntüsü bayt dizisi olarak. |
|
|  | x | double | Ek çerçevesinin x-koordinatı (puan cinsinden). |
|
|  | y | double | Ek çerçevesinin y-koordinatı (puan cinsinden). |
|
|  | width | double | Eklenti çerçevesinin nokta cinsinden genişliği. |
|
|  | height | double | Eklenti çerçevesinin nokta cinsinden yüksekliği. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

