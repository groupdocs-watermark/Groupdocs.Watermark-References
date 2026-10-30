---
title: "FileType"
second_title: "GroupDocs.Watermark for .NET API Referansı"
description: "Dosya türünü temsil eder."
type: docs
weight: 40
url: /tr/net/groupdocs.watermark.common/filetype/
---
## FileType class

Dosya türünü temsil eder.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Dosya adı uzantısını (nokta "." dahil) alır, ör. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Dosya türü adını alır, ör. "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Biçim ailesini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Dosya uzantısını dosya türüne eşler. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Mevcut [`FileType`](../filetype) nesnesinin belirtilen [`FileType`](../filetype) nesnesiyle aynı olup olmadığını belirler. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Mevcut [`FileType`](../filetype) nesnesinin belirtilen nesneyle aynı olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Mevcut [`FileType`](../filetype) nesnesi için bir karma kodu döndürür. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Mevcut nesneyi temsil eden bir dize döndürür. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Desteklenen dosya türlerini alır. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | İki [`FileType`](../filetype) nesnesinin aynı olup olmadığını belirler. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | İki [`FileType`](../filetype) nesnesinin aynı olmadığını belirler. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Uzantısı .BMP olan dosyalar, bitmap dijital görüntüleri depolamak için kullanılan Bitmap Image dosyalarını temsil eder. Bu görüntüler grafik adaptöründen bağımsızdır ve cihaz bağımsız bitmap (DIB) dosya formatı olarak da adlandırılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Uzantısı .doc olan dosyalar, Microsoft Word veya diğer kelime işlemci programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulan belgelerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX, Microsoft Word belgeleri için yaygın bir formattır. 2007'de Microsoft Office 2007'nin yayınlanmasıyla tanıtılan bu yeni belge formatının yapısı, düz ikili formatından XML ve ikili dosyaların bir kombinasyonuna değiştirildi. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Uzantısı .DOT olan dosyalar, sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulan şablon dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Uzantısı .DOTX olan dosyalar, sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML dosya formatı, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX dosya formatı Apple tarafından uygulanmış ve geliştirilmiştir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML, ZIP paketi (.xml) yerine düz bir XML dosyasında depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Makro Etkin Belgesi, ZIP paketi (.xml) yerine düz bir XML dosyasında depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML Şablonu (makrosuz), ZIP paketi (.xml) yerine düz bir XML dosyasında depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Makro Etkin Şablonu, ZIP paketi (.xml) yerine düz bir XML dosyasında depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF veya Graphical Interchange Format, yüksek sıkıştırmalı bir görüntü türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG, kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF), bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. Dalga boyu teknolojisi kullanılarak tasarlanan JPEG 2000, kayıpsız içeriği tek seferde herhangi bir kalitede kodlayabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG, kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM), bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. Dalga boyu teknolojisi kullanılarak tasarlanan JPEG 2000, kayıpsız içeriği herhangi bir kalitede anında kodlayabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX), bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. Dalga boyu teknolojisi kullanılarak tasarlanan JPEG 2000, kayıpsız içeriği herhangi bir kalitede anında kodlayabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. Bu dosyalar, ücretsiz OpenOffice Writer gibi kelime işlemci uygulamalarıyla oluşturulur ve metin, görüntü, nesne ve stiller gibi içerikleri barındırabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | .OFT uzantılı dosyalar, Microsoft Outlook kullanılarak oluşturulan mesaj şablonu dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML dosyası (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Taşınabilir Belge Formatı (PDF), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. Bu dosya formatının amacı, belgelerin ve diğer referans materyallerinin uygulama yazılımı, donanım ve işletim sisteminden bağımsız bir formatta temsil edilmesi için bir standart getirmekti. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Taşınabilir Ağ Grafikleri, kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatını ifade eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | POTM uzantılı dosyalar, makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları, PowerPoint 2007 veya üzeri sürümlerle oluşturulur ve sonraki sunum dosyalarını oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | .POTX uzantılı dosyalar, Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slayt Gösterisi, dosyaları, slayt gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosyalarının okunması ve oluşturulması Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkinleştirilmiş slayt gösterisi dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, PowerPoint Slayt Gösterisi, dosyaları, slayt gösterisi amacıyla Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT uzantılı bir dosya, slayt gösterisi olarak görüntülenmek üzere bir dizi slayt içeren PowerPoint dosyasını temsil eder. Bu, Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkinleştirilmiş sunum dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX uzantılı dosyalar, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. Önceki PPT sunum dosyası formatının ikili olmasının aksine, PPTX formatı Microsoft PowerPoint açık XML sunum dosyası formatına dayanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft tarafından tanıtılan ve belgelenen Rich Text Format (RTF), biçimlendirilmiş metin ve grafiklerin uygulamalar içinde kullanılmak üzere kodlanmasının bir yöntemini temsil eder. Bu format, diğer Microsoft Ürünleriyle çapraz platform belge değişimini kolaylaştırarak birlikte çalışabilirlik amacını hizmet eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF veya TIF, Tagged Image File Format, bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere raster görüntüleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF veya TIF, Tagged Image File Format, bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere raster görüntüleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Bilinmeyen dosya türünü temsil eder. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW, Web çizimi oluşturmak için gerekli akışları ve depolamaları belirten Visio Graphics Service dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio'da oluşturulan ancak XML formatında kaydedilen herhangi bir çizim veya grafik .VDX uzantısına sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD dosyaları, Microsoft Visio uygulamasıyla oluşturulan ve çeşitli grafik nesneleri ile bunların birbirleriyle olan bağlantılarını temsil eden çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | VSDM uzantılı dosyalar, makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | VSDX uzantılı dosyalar, Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS, Microsoft Visio 2007 ve öncesi sürümlerle oluşturulan şablon dosyalarıdır. Şablon dosyaları, .VSD Visio çizimine dahil edilebilecek çizim nesneleri sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | VSSM uzantılı dosyalar, makroları destekleyen Microsoft Visio Şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | VSSX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonlarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST uzantılı dosyalar, Microsoft Visio ile oluşturulan ve daha sonraki dosyalar oluşturmak için şablon olarak kullanılan vektör görüntü dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM uzantılı dosyalar, makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | VSTX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | VSX uzantılı dosyalar, Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekiller içeren şablonları ifade eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX uzantılı dosya, XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, Google tarafından tanıtılan, kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web görüntü dosya formatıdır. Aynı görüntü kalitesini sağlarken görüntü boyutunu önemli ölçüde azaltır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS uzantılı dosyalar, Excel Binary File Format'ı temsil eder. Bu dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer tablo programları tarafından da oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB dosya formatı, Excel Binary File Format'ı belirtir; bu, Excel çalışma kitabı içeriğini tanımlayan kayıtlar ve yapılar koleksiyonudur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | XLSM uzantılı dosyalar, makroları destekleyen bir tür elektronik tablo dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX, Microsoft Office 2007 sürümüyle Microsoft tarafından tanıtılan Microsoft Excel belgeleri için yaygın bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | .XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olan bir elektronik tablo uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM dosya uzantısı, Microsoft Excel tarafından Makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX uzantılı dosyalar, Office OpenXML dosya formatı spesifikasyonlarına dayanan Microsoft Excel Şablon dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Açıklamalar

Bu sınıf, **GroupDocs.Watermark** tarafından desteklenen tüm dosya türlerinin listesini elde etmek için yöntemler sağlar.**Daha fazla bilgi**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Ayrıca Bakınız

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
