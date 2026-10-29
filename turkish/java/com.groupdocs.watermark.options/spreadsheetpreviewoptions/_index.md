---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Elektronik tablo belgesi için ön izleme oluşturma gereksinimlerini ve akış delegelerini ayarlama seçenekleri sağlar."
type: docs
weight: 52
url: /tr/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Elektronik tablo belgesi için ön izleme oluşturma gereksinimlerini ve akış delegelerini ayarlama seçenekleri sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Çıktı akışının kapatılmasına neden olacak şekilde yeni bir `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` sınıfı örneği başlatır. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Çıktı akışının istemciye geri gönderilerek daha sonra kullanılmasına neden olacak şekilde yeni bir `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` sınıfı örneği başlatır. |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Üstbilgi, altbilgi ve kenar boşlukları olmadan yalnızca veri alanını renderlemek için bayrağı alır. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Üstbilgi, altbilgi ve kenar boşlukları olmadan yalnızca veri alanını renderlemek için bayrağı ayarlar. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Çıktı akışının kapatılmasına neden olacak şekilde yeni bir `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` sınıfı örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Çıktı akışının istemciye geri gönderilerek daha sonra kullanılmasına neden olacak şekilde yeni bir `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` sınıfı örneği başlatır.


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

Varsayılan değer 96'dır.

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

Varsayılan değer 96'dır.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Üstbilgi, altbilgi ve kenar boşlukları olmadan yalnızca veri alanını renderlemek için bayrağı alır.


**Returns:**
boolean - Üstbilgi, altbilgi ve kenar boşlukları olmadan yalnızca veri alanını renderlemek için bayrak.

<br />

*** ** * ** ***

Bu bayrak, tüm çalışma sayfasının tek bir sayfada renderlenmesine yol açar. Varsayılan değer false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Üstbilgi, altbilgi ve kenar boşlukları olmadan yalnızca veri alanını renderlemek için bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Üstbilgi, altbilgi ve kenar boşlukları olmadan yalnızca veri alanını renderlemek için bayrak. |

<br />

*** ** * ** ***

Bu bayrak, tüm çalışma sayfasının tek bir sayfada renderlenmesine yol açar. Varsayılan değer false.

<br />

|

