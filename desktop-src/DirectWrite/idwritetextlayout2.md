---
title: IDWriteTextLayout2 interface
description: Represents a block of text after it has been fully analyzed and formatted.
ms.assetid: 034D795B-016A-401E-AD75-D5B0D1E87806
keywords:
- IDWriteTextLayout2 interface Direct Write
- IDWriteTextLayout2 interface Direct Write , described
topic_type:
- apiref
api_name:
- IDWriteTextLayout2
api_location:
- dwrite.dll
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: interface
ms.date: 05/31/2018
---

# IDWriteTextLayout2 interface

Represents a block of text after it has been fully analyzed and formatted.

## Members

The **IDWriteTextLayout2** interface inherits from [**IDWriteTextLayout1**](/windows/desktop/api/dwrite_1/). **IDWriteTextLayout2** also has these types of members:

-   [Methods](#methods)

### Methods

The **IDWriteTextLayout2** interface has these methods.



| Method                                                                                | Description                                                                                 |
|:--------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------|
| [**GetFontFallback**](/windows/desktop/api/dwrite_2/)                         | Get the current font fallback object. <br/>                                           |
| [**GetLastLineWrapping**](/windows/desktop/api/dwrite_2/)                 | Get whether or not the last word on the last line is wrapped.<br/>                    |
| [**GetMetrics**](idwritetextlayout2-getmetrics.md)                                   | Retrieves overall metrics for the formatted string. <br/>                             |
| [**GetOpticalAlignment**](/windows/desktop/api/dwrite_2/)                 | Get how the glyphs align to the edges the margin. <br/>                               |
| [**GetVerticalGlyphOrientation**](/windows/desktop/api/dwrite_2/) | Get the preferred orientation of glyphs when using a vertical reading direction.<br/> |
| [**SetFontFallback**](/windows/desktop/api/dwrite_2/)                         | Apply a custom font fallback onto layout.<br/>                                        |
| [**SetLastLineWrapping**](/windows/desktop/api/dwrite_2/)                 | Set whether or not the last word on the last line is wrapped. <br/>                   |
| [**SetOpticalAlignment**](/windows/desktop/api/dwrite_2/)                 | Set how the glyphs align to the edges the margin.<br/>                                |
| [**SetVerticalGlyphOrientation**](/windows/desktop/api/dwrite_2/) | Set the preferred orientation of glyphs when using a vertical reading direction.<br/> |



 

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8.1 \[desktop apps \| UWP apps\]<br/>                                     |
| Minimum supported server<br/> | Windows Server 2012 R2 \[desktop apps \| UWP apps\]<br/>                          |
| Minimum supported phone<br/>  | Windows Phone 8.1 \[Windows Phone Silverlight 8.1 and Windows Runtime apps\]<br/> |
| Library<br/>                  | <dl> <dt>Dwrite.lib</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Dwrite.dll</dt> </dl>   |



## See also

<dl> <dt>

[**IDWriteTextLayout1**](/windows/desktop/api/dwrite_1/)
</dt> </dl>

 

 




