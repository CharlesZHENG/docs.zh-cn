---
title: "ICLRDebugging 接口"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: ICLRDebugging
api_location: mscordbi.dll
api_type: COM
f1_keywords: ICLRDebugging
helpviewer_keywords: ICLRDebugging interface [.NET Framework debugging]
ms.assetid: 429d8fce-b1b1-49d7-895c-28c1c1aa2dbd
topic_type: apiref
caps.latest.revision: "12"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.workload: dotnet
ms.openlocfilehash: 325f6adf8fe3a357f903f0cb047a2255ef80e264
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="iclrdebugging-interface"></a>ICLRDebugging 接口
提供一些方法，用于处理模块的加载和卸载以进行调试。  
  
## <a name="methods"></a>方法  
  
|方法|描述|  
|------------|-----------------|  
|[OpenVirtualProcess 方法](../../../../docs/framework/unmanaged-api/debugging/iclrdebugging-openvirtualprocess-method.md)|获取对应于进程中加载了公共语言运行时 (CLR) 模块的"ICorDebugProcess"接口。|  
|[CanUnloadNow 方法](../../../../docs/framework/unmanaged-api/debugging/iclrdebugging-canunloadnow-method.md)|确定是否由库[ICLRDebuggingLibraryProvider](../../../../docs/framework/unmanaged-api/debugging/iclrdebugginglibraryprovider-interface.md)接口仍在使用或可以卸载。|  
  
## <a name="remarks"></a>备注  
 你可以获取的实例`ICLRDebugging`接口使用[CLRCreateInstance](../../../../docs/framework/unmanaged-api/hosting/clrcreateinstance-function.md)函数。  
  
## <a name="requirements"></a>惠?  
 **平台：**请参阅[系统要求](../../../../docs/framework/get-started/system-requirements.md)。  
  
 **标头：** CorDebug.idl、 CorDebug.h  
  
 **库：** CorGuids.lib  
  
 **.NET framework 版本：**[!INCLUDE[net_current_v40plus](../../../../includes/net-current-v40plus-md.md)]  
  
## <a name="see-also"></a>请参阅  
 [调试接口](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)  
 [调试](../../../../docs/framework/unmanaged-api/debugging/index.md)
