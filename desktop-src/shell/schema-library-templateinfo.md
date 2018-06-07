---
Description: The &lt;templateInfo&gt; element is a container for the folderType element, which specifies a folder type for displaying the results from a query over this library. This element is optional and has no attributes.
ms.assetid: C555097A-E7B8-45ef-8CFA-19CFBC5E9D5A
title: templateInfo Element (Library Schema)
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# templateInfo Element (Library Schema)

The &lt;templateInfo&gt; element is a container for the [folderType](schema-library-foldertype.md) element, which specifies a folder type for displaying the results from a query over this library. This element is optional and has no attributes.

## Syntax

``` syntax
<!-- templateInfo -->
<xs:element name="templateInfo" minOccurs="0">
    <xs:complexType>
        <xs:all>
            <xs:element name="folderType" minOccurs="0"/>
        </xs:all>
    </xs:complexType>
</xs:element>
```

## Element Information



| Parent Element                                                               | Child Elements                                                             |
|------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| [libraryDescription Element (Library Schema)](schema-librarydescription.md) | [folderType Element (Library Schema)](schema-library-foldertype.md)       |
|                                                                              | [propertyStore Element (Library Schema)](schema-library-propertystore.md) |



 

## Related topics

<dl> <dt>

[Library Description Schema](library-schema-entry.md)
</dt> <dt>

[Search Connector Description Schema](b85a04c6-9398-4cc7-a894-881216600203)
</dt> </dl>

 

 


