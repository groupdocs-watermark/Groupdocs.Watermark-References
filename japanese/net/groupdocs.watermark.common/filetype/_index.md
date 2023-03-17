---
title: FileType
second_title: GroupDocs.Watermark for .NET API リファレンス
description: ファイルの種類を表します
type: docs
weight: 40
url: /ja/net/groupdocs.watermark.common/filetype/
---
## FileType class

ファイルの種類を表します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | ファイル名のサフィックス (ピリオド "." を含む) を取得します (例: ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | ファイル タイプ名を取得します。たとえば、「Microsoft Word ドキュメント」. |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | 形式ファミリを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | ファイル拡張子をファイル タイプにマップします。 |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | 現在の[`FileType`](../filetype)指定と同じです[`FileType`](../filetype)object. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | 現在の[`FileType`](../filetype)指定されたオブジェクトと同じです. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | 現在のハッシュ コードを返します。[`FileType`](../filetype)object. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | サポートされているファイル タイプを取得します。 |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | 2 つの[`FileType`](../filetype)オブジェクトは同じです. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | 2 つの[`FileType`](../filetype)オブジェクトは同じではありません. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | 拡張子が .BMP のファイルは、ビットマップ デジタル イメージを格納するために使用されるビットマップ イメージ ファイルを表します。このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | 拡張子が .doc のファイルは、Microsoft Word またはその他のワード プロセッシングによって生成されたドキュメントを表します ドキュメントはバイナリ ファイル形式です。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年に Microsoft Office 2007 の release で導入されたこの新しいドキュメント形式の構造は、単純な binary から XML とバイナリ ファイルの組み合わせに変更されました。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | 拡張子が .DOT のファイルは、Microsoft Word によって作成されたテンプレート ファイルであり、さらに DOC または DOCX ファイルを生成するための事前に書式設定された設定 を持っています。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM 拡張子を持つファイルは、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | DOTX 拡張子を持つファイルは、Microsoft Word によって作成されたテンプレート ファイルであり、さらに DOCX ファイルを生成するための事前にフォーマットされた設定 を持っています。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML ファイル形式は、Outlook およびその他の関連アプリケーションを使用して保存された電子メール メッセージを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX ファイル形式は、Apple によって実装および開発されています。 Apple Mail アプリケーションは、電子メールのエクスポートに EMLX ファイル形式を使用します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML は、ZIP パッケージ (.xml) ではなくフラットな XML ファイルに格納されています。 このファイル形式の詳細[ここ](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML マクロ対応ドキュメントは、ZIP パッケージ (.xml) ではなく、フラットな XML ファイルに保存されます。 このファイル形式の詳細[ここ](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML テンプレート (マクロなし) は、ZIP パッケージ (.xml) ではなく、フラットな XML ファイルに保存されます。 このファイル形式の詳細[ここ](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML マクロ対応テンプレートは、ZIP パッケージ (.xml) ではなく、フラットな XML ファイルに保存されます。 このファイル形式の詳細[ここ](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF または Graphical Interchange Format は、高度に圧縮された画像の一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG は、非可逆圧縮方式を使用して保存される画像形式の一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、あらゆる品質のロスレス コンテンツを一度にコーディングできます。詳しくは このファイル形式について[ここ](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG は、非可逆圧縮方式を使用して保存される画像形式の一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、あらゆる品質のロスレス コンテンツを一度にコーディングできます。詳しくは このファイル形式について[ここ](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、あらゆる品質のロスレス コンテンツを一度にコーディングできます。詳しくは このファイル形式について[ここ](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG は、電子メール メッセージ、連絡先、 予定、またはその他のタスクを保存するために Microsoft Outlook および Exchange で使用されるファイル形式です。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT ファイルは、OpenDocument テキスト ファイル形式に基づくワード プロセッシング アプリケーションで作成されたドキュメントのタイプです。これらは無料の OpenOffice Writer などのワープロ アプリケーションで作成され、 はテキスト、画像、オブジェクト、スタイルなどのコンテンツを保持できます。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | 拡張子が .OFT のファイルは、Microsoft Outlook を使用して作成されたメッセージ テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office オープン xml ファイル (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) は、1990 年代に Adobe によって作成されたドキュメントの一種です。この ファイル形式の目的は、アプリケーション ソフトウェア、ハードウェア、およびオペレーティング システムに依存しない 形式でドキュメントやその他の参照資料を表現するための標準を導入することでした。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG (Portable Network Graphics) は、ロスレス圧縮を使用するラスター イメージ ファイル形式の一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | POTM 拡張子を持つファイルは、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。 POTM ファイル は PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成 するために使用できるデフォルト設定が含まれています。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | 拡張子が .POTX のファイルは、 Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS、PowerPoint スライド ショー、ファイルは、スライド ショーの目的で Microsoft PowerPoint を使用して作成されます。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM 拡張子を持つファイルは、Microsoft PowerPoint 2007 以降で作成されたマクロ有効スライド ショー ファイル形式を表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX、Power Point スライド ショー、ファイルは、 スライド ショーの目的で Microsoft PowerPoint 2007 以降を使用して作成されます。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | 拡張子が PPT のファイルは、スライドショーとして表示される 用のスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM 拡張子を持つファイルは、 Microsoft PowerPoint 2007 以降のバージョンで作成された、マクロが有効なプレゼンテーション ファイルです。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | 拡張子が PPTX のファイルは、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft によって導入および文書化されたリッチ テキスト形式 (RTF) は、アプリケーション内で使用する 形式のテキストとグラフィックスをエンコードする方法を表します。この形式は、他の Microsoft 製品とのクロスプラットフォームの document 交換を容易にし、相互運用性の目的を果たします。詳しくは このファイル形式について[ここ](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF または TIF、Tagged Image File Format は、このファイル形式標準に準拠するさまざまな デバイスで使用するためのラスター イメージを表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF または TIF、Tagged Image File Format は、このファイル形式標準に準拠するさまざまな デバイスで使用するためのラスター イメージを表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | 不明なファイル タイプを表します。 |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW は、Web 図面の レンダリングに必要なストリームとストレージを指定する Visio Graphics Service ファイル形式です。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio で作成され、XML 形式で保存された図面またはチャートには、拡張子 .VDX が付きます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD ファイルは、さまざまなグラフィカル オブジェクトとこれらの間の相互接続を表すために Microsoft Visio アプリケーションで作成された図面です。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | 拡張子が VSDM のファイルは、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。 このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | 拡張子が .VSDX のファイルは、Microsoft Office 2013 以降で導入された Microsoft Visio ファイル形式を表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS は、Microsoft Visio 2007 以前で作成されたステンシル ファイルです。ステンシル ファイルは、.VSD Visio 図面に含めることができる drawing オブジェクトを提供します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | 拡張子が .VSSM のファイルは、マクロをサポートする Microsoft Visio Stencil ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | 拡張子が .VSSX のファイルは、Microsoft Visio 2013 以降で作成された図面ステンシルです。 このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST 拡張子を持つファイルは、Microsoft Visio で作成されたベクター画像ファイルであり、さらにファイルを作成する のテンプレートとして機能します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM 拡張子を持つファイルは、マクロをサポートする Microsoft Visio で作成されたテンプレート ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | 拡張子が VSTX のファイルは、Microsoft Visio 2013 以降で作成された図面テンプレート ファイルです。 このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | 拡張子が .VSX のファイルは、Microsoft Visio で 図を作成するために使用される図面と図形で構成されるステンシルを指します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX 拡張子を持つファイルは、XML ファイル形式でディスクに保存される Microsoft Visio 図面テンプレートです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | Google によって導入された WebP は、可逆圧縮および 非可逆圧縮に基づく最新のラスター Web イメージ ファイル形式です。画像サイズを大幅に縮小しながら、同じ画質を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS 拡張子を持つファイルは、Excel Binary File Format を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。詳しくは このファイル形式について[ここ](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB ファイル形式は、Excel ブックのコンテンツを指定するレコードと 構造体のコレクションである Excel バイナリ ファイル形式を指定します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | 拡張子が XLSM のファイルは、マクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX は、Microsoft Office 2007 のリリース で Microsoft によって導入された、Microsoft Excel ドキュメントのよく知られた形式です。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | 拡張子が .XLT のファイルは、Microsoft Office スイートの一部として提供されるスプレッドシート アプリケーションである Microsoft Excel で作成されたテンプレート ファイルです。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM ファイル拡張子は、マクロが有効な テンプレート ファイルとして Microsoft Excel によって生成されるファイルを表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | 拡張子が XLTX のファイルは、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレート ファイルを表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### 備考

このクラスは、サポートされているすべてのファイル タイプのリストを取得するメソッドを提供します。**GroupDocs.透かし**.**もっと詳しく知る**

* [サポートされているドキュメント形式](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [サポートされているファイル形式を取得する](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [ドキュメント情報を取得する](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 関連項目

* 名前空間 [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* 組み立て [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
