---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belgesinin ön izleme oluşturulması için gereksinimleri ve akış delegelerini ayarlamak üzere seçenekler sağlar."
type: docs
weight: 31
url: /tr/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

PDF belgesinin ön izleme oluşturulması için gereksinimleri ve akış delegelerini ayarlamak üzere seçenekler sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Çıktı akışının kapatılmasına neden olacak şekilde yeni bir `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` sınıf örneği oluşturur. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Çıktı akışının istemciye daha sonraki kullanım için geri döndürülmesine neden olacak şekilde yeni bir `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` sınıf örneği oluşturur. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Varsayılan çözünürlük inç başına nokta (dpi) cinsinden. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getResolution()](#getResolution--) | Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden alır. |
|
|  | [setResolution(int value)](#setResolution-int-) | Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden ayarlar. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Çıktı akışının kapatılmasına neden olacak şekilde yeni bir `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` sınıf örneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Çıktı akışının istemciye daha sonraki kullanım için geri döndürülmesine neden olacak şekilde yeni bir `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` sınıf örneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Varsayılan çözünürlük inç başına nokta (dpi) cinsinden.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden alır.


**Returns:**
int - Oluşturulan görüntüler için çözünürlük, inç başına nokta (dpi) cinsinden.

<br />

*** ** * ** ***

Varsayılan değer 150'dir.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Oluşturulan görüntüler için çözünürlük, inç başına nokta (dpi) cinsinden. |

<br />

*** ** * ** ***

Varsayılan değer 150'dir.

<br />

|

