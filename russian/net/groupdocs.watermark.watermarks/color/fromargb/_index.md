---
title: "FromArgb"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Создает структуру Colorgroupdocs.watermark.watermarks/color из 32‑битного значения ARGB."
type: docs
weight: 1430
url: /ru/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Создает структуру [`Color`](../../color) из 32‑битного значения ARGB.

```csharp
public static Color FromArgb(int argb)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| argb | Int32 | Значение, указывающее 32‑битное значение ARGB. |

### Возвращаемое значение

Структура [`Color`](../../color), которую создает этот метод.

### См. также

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Создает структуру [`Color`](../../color) из указанной структуры [`Color`](../../color), но с новым указанным альфа‑значением.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Int32 | Альфа‑значение для новой [`Color`](../../color). Допустимые значения от 0 до 255. |
| baseColor | Color | Структура [`Color`](../../color), из которой создаётся новая [`Color`](../../color). |

### Возвращаемое значение

Структура [`Color`](../../color), которую создает этот метод.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Альфа меньше 0 или больше 255. |

### Примечания

Хотя этот метод позволяет передать 32‑битное значение для альфа‑значения, значение ограничено 8‑битами.

### См. также

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Создает структуру [`Color`](../../color) из указанных 8‑битных значений цветов (красный, зелёный и синий), при этом альфа‑значение неявно равно 255 (полностью непрозрачное).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| red | Int32 | Значение красного компонента для новой [`Color`](../../color). Допустимые значения от 0 до 255. |
| green | Int32 | Значение зелёного компонента для новой [`Color`](../../color). Допустимые значения от 0 до 255. |
| blue | Int32 | Значение синего компонента для нового [`Color`](../../color). Допустимые значения от 0 до 255. |

### Возвращаемое значение

Структура [`Color`](../../color), которую создает этот метод.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Красный, зелёный или синий меньше 0 или больше 255. |

### Примечания

Хотя этот метод позволяет передавать 32‑битное значение для каждого цветового компонента, значение каждого компонента ограничено 8 битами.

### См. также

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Создаёт структуру [`Color`](../../color) из четырёх значений компонентов ARGB (альфа, красный, зелёный и синий).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Int32 | Значение альфа‑компонента для нового [`Color`](../../color). Допустимые значения от 0 до 255. |
| red | Int32 | Значение красного компонента для новой [`Color`](../../color). Допустимые значения от 0 до 255. |
| green | Int32 | Значение зелёного компонента для новой [`Color`](../../color). Допустимые значения от 0 до 255. |
| blue | Int32 | Значение синего компонента для нового [`Color`](../../color). Допустимые значения от 0 до 255. |

### Возвращаемое значение

Структура [`Color`](../../color), которую создает этот метод.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Красный, зелёный или синий меньше 0 или больше 255. |

### Примечания

Хотя этот метод позволяет передавать 32‑битное значение для каждого компонента, значение каждого компонента ограничено 8 битами.

### См. также

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
