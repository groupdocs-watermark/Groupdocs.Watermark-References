---
title: Save
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Enregistre les données du document dans le flux sousjacent.
type: docs
weight: 100
url: /fr/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Enregistre les données du document dans le flux sous-jacent.

```csharp
public void Save()
```

### Remarques

En savoir plus sur l'enregistrement des documents [Enregistrement de documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exemples

Supprimez des fragments de texte particuliers du corps/de l'objet de l'e-mail et enregistrez l'e-mail.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Remarque, la recherche n'est effectuée que si vous passez l'instance TextSearchCriteria à la méthode Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Supprime les fragments de texte trouvés
    watermarker.Remove(watermarks);
    // Sauvegarder les modifications
    watermarker.Save();
}
```

### Voir également

* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Enregistre le document à l'emplacement de fichier spécifié.

```csharp
public void Save(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier dans lequel enregistrer les données du document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Enregistrement de documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exemples

Ajoutez le filigrane et enregistrez le document dans un autre fichier.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Voir également

* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Enregistre le document dans le flux spécifié.

```csharp
public void Save(Stream document)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux dans lequel enregistrer les données du document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Enregistrement de documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exemples

Ajoutez un filigrane et enregistrez le document dans le flux de mémoire.

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

### Voir également

* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Enregistre les données du document dans le flux sous-jacent à l'aide des options d'enregistrement.

```csharp
public void Save(SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | SaveOptions | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Enregistrement de documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exemples

Ajoutez un filigrane et enregistrez le document par défaut[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Voir également

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Enregistre le document à l'emplacement de fichier spécifié à l'aide des options d'enregistrement.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier dans lequel enregistrer les données du document. |
| options | SaveOptions | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Enregistrement de documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exemples

Ajoutez le filigrane et enregistrez le document dans un autre fichier par défaut[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Voir également

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Enregistre le document dans le flux spécifié à l'aide des options d'enregistrement.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux dans lequel enregistrer les données du document. |
| options | SaveOptions | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |

### Remarques

En savoir plus sur l'enregistrement des documents [Enregistrement de documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exemples

Ajoutez un filigrane et enregistrez le document dans le flux de mémoire par défaut[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

### Voir également

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
