---
title: JET_ERRINFOBASIC.rgCategoricalHierarchy property  (Microsoft.Isam.Esent.Interop.Windows8)
TOCTitle: 'rgCategoricalHierarchy property '
ms:assetid: P:Microsoft.Isam.Esent.Interop.Windows8.JET_ERRINFOBASIC.rgCategoricalHierarchy
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.windows8.jet_errinfobasic.rgcategoricalhierarchy(v=EXCHG.10)
ms:contentKeyID: 55104314
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
f1_keywords:
- Microsoft.Isam.Esent.Interop.Windows8.JET_ERRINFOBASIC.rgCategoricalHierarchy
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.Windows8.JET_ERRINFOBASIC.set_rgCategoricalHierarchy
- Microsoft.Isam.Esent.Interop.Windows8.JET_ERRINFOBASIC.get_rgCategoricalHierarchy
- Microsoft.Isam.Esent.Interop.Windows8.JET_ERRINFOBASIC.rgCategoricalHierarchy
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET\_ERRINFOBASIC.rgCategoricalHierarchy property

Gets or sets the hierarchy of errors. Position 0 is the highest level in the hierarchy, and the rest are JET\_errcatUnknown.

**Namespace:**  [Microsoft.Isam.Esent.Interop.Windows8](dn335439\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Property rgCategoricalHierarchy As JET_ERRCAT()
    Get
    Set
'Usage
Dim instance As JET_ERRINFOBASIC
Dim value As JET_ERRCAT()

value = instance.rgCategoricalHierarchy

instance.rgCategoricalHierarchy = value
```

``` csharp
public JET_ERRCAT[] rgCategoricalHierarchy { get; set; }
```

#### Property value

Type: \[\]  

## See also

#### Reference

[JET\_ERRINFOBASIC class](dn335334\(v=exchg.10\).md)

[JET\_ERRINFOBASIC members](dn335336\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop.Windows8 namespace](dn335439\(v=exchg.10\).md)
