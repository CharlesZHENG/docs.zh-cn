---
title: "ICorDebugModule 接口 1"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: ICorDebugModule
api_location: mscordbi.dll
api_type: COM
f1_keywords: ICorDebugModule
helpviewer_keywords: ICorDebugModule interface [.NET Framework debugging]
ms.assetid: 32e4d6fa-e5a3-413e-9166-d5e2871d3114
topic_type: apiref
caps.latest.revision: "13"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.openlocfilehash: ced01c9c01a32468f371a8e172c878337fb79757
ms.sourcegitcommit: 4f3fef493080a43e70e951223894768d36ce430a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/21/2017
---
# <a name="icordebugmodule-interface1"></a><span data-ttu-id="54641-102">ICorDebugModule 接口 1</span><span class="sxs-lookup"><span data-stu-id="54641-102">ICorDebugModule Interface1</span></span>
<span data-ttu-id="54641-103">表示公共语言运行时 (CLR) 模块，这是可执行文件或动态链接库 (DLL)。</span><span class="sxs-lookup"><span data-stu-id="54641-103">Represents a common language runtime (CLR) module, which is either an executable file or a dynamic-link library (DLL).</span></span>  
  
## <a name="methods"></a><span data-ttu-id="54641-104">方法</span><span class="sxs-lookup"><span data-stu-id="54641-104">Methods</span></span>  
  
|<span data-ttu-id="54641-105">方法</span><span class="sxs-lookup"><span data-stu-id="54641-105">Method</span></span>|<span data-ttu-id="54641-106">描述</span><span class="sxs-lookup"><span data-stu-id="54641-106">Description</span></span>|  
|------------|-----------------|  
|[<span data-ttu-id="54641-107">CreateBreakpoint 方法</span><span class="sxs-lookup"><span data-stu-id="54641-107">CreateBreakpoint Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-createbreakpoint-method.md)|<span data-ttu-id="54641-108">未实现。</span><span class="sxs-lookup"><span data-stu-id="54641-108">Not implemented.</span></span>|  
|[<span data-ttu-id="54641-109">EnableClassLoadCallbacks 方法</span><span class="sxs-lookup"><span data-stu-id="54641-109">EnableClassLoadCallbacks Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-enableclassloadcallbacks-method.md)|<span data-ttu-id="54641-110">确定是否[icordebugmanagedcallback:: Loadclass](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-loadclass-method.md)和[icordebugmanagedcallback:: Unloadclass](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-unloadclass-method.md)回调调用此模块。</span><span class="sxs-lookup"><span data-stu-id="54641-110">Determines whether the [ICorDebugManagedCallback::LoadClass](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-loadclass-method.md) and [ICorDebugManagedCallback::UnloadClass](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-unloadclass-method.md) callbacks are called for this module.</span></span>|  
|[<span data-ttu-id="54641-111">EnableJITDebugging 方法</span><span class="sxs-lookup"><span data-stu-id="54641-111">EnableJITDebugging Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-enablejitdebugging-method.md)|<span data-ttu-id="54641-112">确定是否在实时 (JIT) 编译器会保留为此模块中的方法的调试信息。</span><span class="sxs-lookup"><span data-stu-id="54641-112">Determines whether the just-in-time (JIT) compiler preserves debugging information for methods within this module.</span></span>|  
|[<span data-ttu-id="54641-113">GetAssembly 方法</span><span class="sxs-lookup"><span data-stu-id="54641-113">GetAssembly Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getassembly-method.md)|<span data-ttu-id="54641-114">获取此模块包含程序集。</span><span class="sxs-lookup"><span data-stu-id="54641-114">Gets the containing assembly for this module.</span></span>|  
|[<span data-ttu-id="54641-115">GetBaseAddress 方法</span><span class="sxs-lookup"><span data-stu-id="54641-115">GetBaseAddress Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getbaseaddress-method.md)|<span data-ttu-id="54641-116">获取模块的基址。</span><span class="sxs-lookup"><span data-stu-id="54641-116">Gets the base address of the module.</span></span>|  
|[<span data-ttu-id="54641-117">GetClassFromToken 方法</span><span class="sxs-lookup"><span data-stu-id="54641-117">GetClassFromToken Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getclassfromtoken-method.md)|<span data-ttu-id="54641-118">获取 ICorDebugClass 从元数据。</span><span class="sxs-lookup"><span data-stu-id="54641-118">Gets the ICorDebugClass from the metadata.</span></span>|  
|[<span data-ttu-id="54641-119">GetEditAndContinueSnapshot 方法</span><span class="sxs-lookup"><span data-stu-id="54641-119">GetEditAndContinueSnapshot Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-geteditandcontinuesnapshot-method.md)|<span data-ttu-id="54641-120">已否决。</span><span class="sxs-lookup"><span data-stu-id="54641-120">Deprecated.</span></span>|  
|[<span data-ttu-id="54641-121">GetFunctionFromRVA 方法</span><span class="sxs-lookup"><span data-stu-id="54641-121">GetFunctionFromRVA Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getfunctionfromrva-method.md)|<span data-ttu-id="54641-122">未实现。</span><span class="sxs-lookup"><span data-stu-id="54641-122">Not implemented.</span></span>|  
|[<span data-ttu-id="54641-123">GetFunctionFromToken 方法</span><span class="sxs-lookup"><span data-stu-id="54641-123">GetFunctionFromToken Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getfunctionfromtoken-method.md)|<span data-ttu-id="54641-124">获取指定元数据标记的函数。</span><span class="sxs-lookup"><span data-stu-id="54641-124">Gets the function that is specified by the metadata token.</span></span>|  
|[<span data-ttu-id="54641-125">GetGlobalVariableValue 方法</span><span class="sxs-lookup"><span data-stu-id="54641-125">GetGlobalVariableValue Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getglobalvariablevalue-method.md)|<span data-ttu-id="54641-126">获取指定的全局变量的值对象。</span><span class="sxs-lookup"><span data-stu-id="54641-126">Gets a value object for the specified global variable.</span></span>|  
|[<span data-ttu-id="54641-127">GetMetaDataInterface 方法</span><span class="sxs-lookup"><span data-stu-id="54641-127">GetMetaDataInterface Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getmetadatainterface-method.md)|<span data-ttu-id="54641-128">获取可用于检查该模块的元数据的元数据接口指针。</span><span class="sxs-lookup"><span data-stu-id="54641-128">Gets a metadata interface pointer that can be used to examine the metadata for the module.</span></span>|  
|[<span data-ttu-id="54641-129">GetName 方法</span><span class="sxs-lookup"><span data-stu-id="54641-129">GetName Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getname-method.md)|<span data-ttu-id="54641-130">获取模块的文件名。</span><span class="sxs-lookup"><span data-stu-id="54641-130">Gets the file name of the module.</span></span>|  
|[<span data-ttu-id="54641-131">GetProcess 方法</span><span class="sxs-lookup"><span data-stu-id="54641-131">GetProcess Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getprocess-method.md)|<span data-ttu-id="54641-132">获取此模块包含进程。</span><span class="sxs-lookup"><span data-stu-id="54641-132">Gets the containing process for this module.</span></span>|  
|[<span data-ttu-id="54641-133">GetSize 方法</span><span class="sxs-lookup"><span data-stu-id="54641-133">GetSize Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-getsize-method.md)|<span data-ttu-id="54641-134">获取用字节表示的模块的大小。</span><span class="sxs-lookup"><span data-stu-id="54641-134">Gets the size of the module in bytes.</span></span>|  
|[<span data-ttu-id="54641-135">GetToken 方法</span><span class="sxs-lookup"><span data-stu-id="54641-135">GetToken Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-gettoken-method.md)|<span data-ttu-id="54641-136">获取此模块的表项的令牌。</span><span class="sxs-lookup"><span data-stu-id="54641-136">Gets the token for the table entry for this module.</span></span>|  
|[<span data-ttu-id="54641-137">IsDynamic 方法</span><span class="sxs-lookup"><span data-stu-id="54641-137">IsDynamic Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-isdynamic-method.md)|<span data-ttu-id="54641-138">指示是否为动态模块。</span><span class="sxs-lookup"><span data-stu-id="54641-138">Indicates whether the module is dynamic.</span></span>|  
|[<span data-ttu-id="54641-139">IsInMemory 方法</span><span class="sxs-lookup"><span data-stu-id="54641-139">IsInMemory Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebugmodule-isinmemory-method.md)|<span data-ttu-id="54641-140">指示仅在内存中是否存在此模块。</span><span class="sxs-lookup"><span data-stu-id="54641-140">Indicates whether this module exists only in memory.</span></span>|  
  
## <a name="remarks"></a><span data-ttu-id="54641-141">备注</span><span class="sxs-lookup"><span data-stu-id="54641-141">Remarks</span></span>  
  
> [!NOTE]
>  <span data-ttu-id="54641-142">此接口不支持跨计算机或跨进程远程调用。</span><span class="sxs-lookup"><span data-stu-id="54641-142">This interface does not support being called remotely, either cross-machine or cross-process.</span></span>  
  
## <a name="requirements"></a><span data-ttu-id="54641-143">要求</span><span class="sxs-lookup"><span data-stu-id="54641-143">Requirements</span></span>  
 <span data-ttu-id="54641-144">**平台：**请参阅[系统要求](../../../../docs/framework/get-started/system-requirements.md)。</span><span class="sxs-lookup"><span data-stu-id="54641-144">**Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).</span></span>  
  
 <span data-ttu-id="54641-145">**标头：** CorDebug.idl、 CorDebug.h</span><span class="sxs-lookup"><span data-stu-id="54641-145">**Header:** CorDebug.idl, CorDebug.h</span></span>  
  
 <span data-ttu-id="54641-146">**库：** CorGuids.lib</span><span class="sxs-lookup"><span data-stu-id="54641-146">**Library:** CorGuids.lib</span></span>  
  
 <span data-ttu-id="54641-147">**.NET framework 版本：**[!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]</span><span class="sxs-lookup"><span data-stu-id="54641-147">**.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="54641-148">另请参阅</span><span class="sxs-lookup"><span data-stu-id="54641-148">See Also</span></span>  
 [<span data-ttu-id="54641-149">ICorDebug 接口</span><span class="sxs-lookup"><span data-stu-id="54641-149">ICorDebug Interface</span></span>](../../../../docs/framework/unmanaged-api/debugging/icordebug-interface.md)  
 [<span data-ttu-id="54641-150">调试接口</span><span class="sxs-lookup"><span data-stu-id="54641-150">Debugging Interfaces</span></span>](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)