---
title: "Compiler Error C2846 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: ["C2846"]
dev_langs: ["C++"]
helpviewer_keywords: ["C2846"]
ms.assetid: bc090ec2-5410-4112-9ec6-261325374375
caps.latest.revision: 9
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Compiler Error C2846
'constructor' : an interface cannot have a constructor  
  
 A Visual C++ [interface](../../cpp/interface.md) cannot have a constructor.  
  
 The following sample generates C2846:  
  
```  
// C2846.cpp  
// compile with: /c  
__interface C {  
   C();   // C2846 constructor not allowed in an interface  
};  
```