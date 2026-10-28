---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά επιλογές προσθήκης υδατογραφήματος όταν προστίθεται υδατογράφημα σχήματος σε ένα έγγραφο Visio."
type: docs
weight: 14
url: /el/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Αναπαριστά επιλογές προσθήκης υδατογραφήματος όταν προστίθεται υδατογράφημα σχήματος σε ένα έγγραφο Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα προστατευμένο υδατογράφημα σε όλες τις σελίδες του εγγράφου Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Λαμβάνει μια τιμή που καθορίζει σε ποιες σελίδες πρέπει να προστεθεί το υδατογράφημα. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Λαμβάνει ή ορίζει μια τιμή που καθορίζει σε ποιες σελίδες πρέπει να προστεθεί το υδατογράφημα. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Λαμβάνει μια τιμή που καθορίζει σε ποιες σελίδες πρέπει να προστεθεί το υδατογράφημα.


**Returns:**
int - Η `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, η οποία καθορίζει σε ποιες σελίδες πρέπει να προστεθεί το υδατογράφημα.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Λαμβάνει ή ορίζει μια τιμή που καθορίζει σε ποιες σελίδες πρέπει να προστεθεί το υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Η `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, η οποία καθορίζει σε ποιες σελίδες πρέπει να προστεθεί το υδατογράφημα. |
|

