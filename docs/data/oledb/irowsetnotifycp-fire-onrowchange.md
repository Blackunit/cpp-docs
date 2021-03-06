---
title: "IRowsetNotifyCP::Fire_OnRowChange | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["IRowsetNotifyCP.Fire_OnRowChange", "ATL.IRowsetNotifyCP.Fire_OnRowChange", "Fire_OnRowChange", "ATL::IRowsetNotifyCP::Fire_OnRowChange", "IRowsetNotifyCP::Fire_OnRowChange"]
dev_langs: ["C++"]
helpviewer_keywords: ["Fire_OnRowChange method"]
ms.assetid: 6f9beed6-7a69-4c92-936f-422e98f3de5c
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# IRowsetNotifyCP::Fire_OnRowChange
Broadcasts an [OnRowChange](https://msdn.microsoft.com/en-us/library/ms722694.aspx) event to all listeners on the connection point **IID_IRowsetNotify** to notify consumers of a change affecting the rows.  
  
## Syntax  
  
```cpp
HRESULT Fire_OnRowChange(IRowset* pRowset,  
   DBCOUNTITEM cRows,  
   const HROW rghRows[],  
   DBREASON eReason,  
   DBEVENTPHASE ePhase,  
   BOOL fCantDeny);  
```  
  
#### Parameters  
 See [IRowsetNotify::OnRowChange](https://msdn.microsoft.com/en-us/library/ms722694.aspx) in the *OLE DB Programmer's Reference*.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetNotifyCP Class](../../data/oledb/irowsetnotifycp-class.md)