---
Description: Allows the callback to add items to the bottom of the extended menu.
title: DFM\_MERGECONTEXTMENU\_BOTTOM message
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# DFM\_MERGECONTEXTMENU\_BOTTOM message

Allows the callback to add items to the bottom of the extended menu.


```C++
DFM_MERGECONTEXTMENU_BOTTOM

    lParam = (LPARAM)(LPQCMINFO) pqcminfo;

    wParam = (WPARAM)(UINT) uFlags;         

            
```



## Parameters

<dl> <dt>

*pqcminfo* \[in\]
</dt> <dd>

A pointer to a [**QCMINFO**](/windows/desktop/api/shlobj_core/ns-shlobj_core-_qcminfo) structure containing the information used in the merge.

</dd> <dt>

*uFlags* \[in\]
</dt> <dd>

Flags specifying how the context menu can be changed. This parameter uses the CMF\_\* values described in [**IContextMenu::QueryContextMenu**](/windows/desktop/api/shobjidl_core/nf-shobjidl_core-icontextmenu-querycontextmenu).

</dd> </dl>

## Remarks

If items are added to the extended context menu, they must be supported with routines that respond appropriately when one of those items is invoked using [**DFM\_INVOKECOMMAND**](dfm-invokecommand.md).

This message is sent to either the callback function or the callback object depending on how the default context menu object is constructed. There are two APIs for its construction, [**CDefFolderMenu\_Create2**](/windows/desktop/api/shlobj_core/nf-shlobj_core-cdeffoldermenu_create2), [**SHCreateDefaultContextMenu**](/windows/desktop/api/shlobj_core/nf-shlobj_core-shcreatedefaultcontextmenu).

[**DFM\_INVOKECOMMANDEX**](dfm-invokecommandex.md) is an extended version of this message and provides more information to the callback. Use **DFM\_INVOKECOMMANDEX** if the additional information provided by that interface is needed in your implementation.

## Requirements



|                                     |                                                                                     |
|-------------------------------------|-------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                      |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                |
| Header<br/>                   | <dl> <dt>Shlobj.h</dt> </dl> |



 

 



