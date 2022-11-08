---
title: Metered
second_title: GroupDocs.Watermark for Java API Reference
description: Provides methods to license the component with Metered license.
type: docs
weight: 11
url: /java/com.groupdocs.watermark.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods to license the component with Metered license.

**Lean more**

 *  More about Metered licensing: [Metered Licensing FAQ][]
 *  More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing][]

The following example demonstrates demonstrates how to activate product with Metered keys.

> ```
> ```
> 
>    string publicKey = "Public Key";
>    string privateKey = "Private Key";
> 
>    Metered metered = new Metered();
>    metered.setMeteredKey(publicKey, privateKey);
>  
> ```
> ```


[Metered Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/watermarkjava/Evaluation+Limitations+and+Licensing
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Initializes a new instance of the `[Metered](../../com.groupdocs.watermark.licensing/metered)` class. |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activates product with Metered keys. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Retrieves amount of MBs processed. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves count of credits consumed. |
### Metered() {#Metered--}
```
public Metered()
```


Initializes a new instance of the `[Metered](../../com.groupdocs.watermark.licensing/metered)` class.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Activates product with Metered keys.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | The public key. |
| privateKey | java.lang.String | The private key. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Retrieves amount of MBs processed.

The following example demonstrates demonstrates how to retrieve amount of MBs processed.

> ```
> ```
> 
>    string publicKey = "Public Key";
>    string privateKey = "Private Key";
> 
>    Metered metered = new Metered();
>    metered.setMeteredKey(publicKey, privateKey);
>  
>    double mbProcessed = Metered.getConsumptionQuantity();
>  
> ```
> ```

**Returns:**
double - The amount of MBs processed.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Retrieves count of credits consumed.

The following example demonstrates demonstrates how to retrieve count of credits consumed.

> ```
> ```
> 
>    string publicKey = "Public Key";
>    string privateKey = "Private Key";
> 
>    Metered metered = new Metered();
>    metered.setMeteredKey(publicKey, privateKey);
>  
>    double creditsConsumed = Metered.getConsumptionCredit();
>  
> ```
> ```

**Returns:**
double - The count of credits consumed.
