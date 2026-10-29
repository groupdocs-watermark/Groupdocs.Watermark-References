---
title: "Enregistrer"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Enregistre les données du document dans le flux sous-jacent."
type: docs
weight: 100
url: /fr/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Enregistre les données du document dans le flux sous-jacent.

```csharp
public WatermarkResult Save()
```

### Remarques

En savoir plus sur l'enregistrement des documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exemples

Supprimer des fragments de texte particuliers du corps/sujet du message électronique et enregistrer le message électronique.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Remarque, la recherche n'est effectuée que si vous transmettez une instance de TextSearchCriteria à la méthode Search.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Supprimer les fragments de texte trouvés
    watermarker.Remove(watermarks);
    // Enregistrer les modifications
    watermarker.Save();
}
```

### Voir aussi

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Enregistre le document à l'emplacement de fichier spécifié.

```csharp
public WatermarkResult Save(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier où enregistrer les données du document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exemples

Ajouter le filigrane et enregistrer le document dans un autre fichier.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Voir aussi

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Enregistre le document dans le flux spécifié.

```csharp
public WatermarkResult Save(Stream document)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux où enregistrer les données du document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exemples

Ajouter le filigrane et enregistrer le document dans le flux mémoire.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### Voir aussi

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Enregistre les données du document dans le flux sous-jacent en utilisant les options d'enregistrement.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exemples

Ajouter un filigrane et enregistrer le document avec les [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) par défaut.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Voir aussi

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Enregistre le document à l'emplacement de fichier spécifié en utilisant les options d'enregistrement.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier où enregistrer les données du document. |
| options | SaveOptions | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exemples

Ajouter le filigrane et enregistrer le document dans un autre fichier avec les [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) par défaut.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Voir aussi

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Enregistre le document dans le flux spécifié en utilisant les options d'enregistrement.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux où enregistrer les données du document. |
| options | SaveOptions | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exemples

Ajouter un filigrane et enregistrer le document dans le flux mémoire avec les [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) par défaut.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### Voir aussi

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
