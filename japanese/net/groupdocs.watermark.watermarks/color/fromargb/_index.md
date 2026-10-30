---
title: "FromArgb"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "32ビット ARGB 値から Colorgroupdocs.watermark.watermarks/color 構造体を作成します。"
type: docs
weight: 1430
url: /ja/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

32ビット ARGB 値から [`Color`](../../color) 構造体を作成します。

```csharp
public static Color FromArgb(int argb)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| argb | Int32 | 32ビット ARGB 値を指定する値です。 |

### 戻り値

このメソッドが作成する [`Color`](../../color) 構造体です。

### 関連項目

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

指定された [`Color`](../../color) 構造体から新しい指定されたアルファ値を使用して [`Color`](../../color) 構造体を作成します。

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| alpha | Int32 | 新しい [`Color`](../../color) のアルファ値です。有効な値は 0 から 255 です。 |
| baseColor | Color | 新しい [`Color`](../../color) を作成する元となる [`Color`](../../color) です。 |

### 戻り値

このメソッドが作成する[`Color`](../../color)です。

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Alpha が 0 未満または 255 より大きいです。 |

### 備考

このメソッドはalpha値に 32 ビットの値を渡すことを許可していますが、値は 8 ビットに制限されます。

### 関連項目

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

指定された 8 ビットのカラー値（red、green、blue）から[`Color`](../../color)構造体を作成し、alpha 値は暗黙的に 255（完全に不透明）になります。

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| red | Int32 | 新しい[`Color`](../../color)の red コンポーネント値です。有効な値は 0 から 255 です。 |
| green | Int32 | 新しい[`Color`](../../color)の green コンポーネント値です。有効な値は 0 から 255 です。 |
| blue | Int32 | 新しい[`Color`](../../color)の blue コンポーネント値です。有効な値は 0 から 255 です。 |

### 戻り値

このメソッドが作成する[`Color`](../../color)です。

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Red、green、または blue が 0 未満または 255 より大きいです。 |

### 備考

このメソッドは各カラーコンポーネントに 32 ビットの値を渡すことを許可していますが、各コンポーネントの値は 8 ビットに制限されます。

### 関連項目

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

4 つの ARGB コンポーネント（alpha、red、green、blue）値から[`Color`](../../color)構造体を作成します。

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| alpha | Int32 | 新しい[`Color`](../../color)の alpha コンポーネント値です。有効な値は 0 から 255 です。 |
| red | Int32 | 新しい[`Color`](../../color)の red コンポーネント値です。有効な値は 0 から 255 です。 |
| green | Int32 | 新しい[`Color`](../../color)の green コンポーネント値です。有効な値は 0 から 255 です。 |
| blue | Int32 | 新しい[`Color`](../../color)の blue コンポーネント値です。有効な値は 0 から 255 です。 |

### 戻り値

このメソッドが作成する[`Color`](../../color)です。

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Red、green、または blue が 0 未満または 255 より大きいです。 |

### 備考

このメソッドは各コンポーネントに 32 ビットの値を渡すことを許可していますが、各コンポーネントの値は 8 ビットに制限されます。

### 関連項目

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
