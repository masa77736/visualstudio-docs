---
title: "IDiaSymbol::get_virtualBaseClass | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaSymbol::get_virtualBaseClass method"
ms.assetid: 474eddc6-bf16-4731-9145-6db2f2a0b4fd
caps.latest.revision: 11
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaSymbol::get_virtualBaseClass
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDiaSymbol::get_virtualBaseClass](https://docs.microsoft.com/visualstudio/debugger/debug-interface-access/idiasymbol-get-virtualbaseclass).  
  
Retrieves a flag that specifies whether the user-defined data type is a virtual base class.  
  
## Syntax  
  
```cpp#  
HRESULT get_virtualBaseClass (   
   BOOL* pRetVal  
);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] Returns `TRUE` if the user-defined data type is a virtual base class; otherwise, returns `FALSE`.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.  
  
> [!NOTE]
>  A return value of `S_FALSE` means the property is not available for the symbol.  
  
## See Also  
 [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)



