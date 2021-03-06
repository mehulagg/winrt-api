---
-api-id: M:Windows.AI.MachineLearning.TensorInt8Bit.CreateReference
-api-type: winrt method
ms.custom: 19H1
---

<!-- Method syntax.
public [IMemoryBufferReference](../windows.foundation/imemorybufferreference.md) TensorInt8Bit.CreateReference()
-->

# Windows.AI.MachineLearning.TensorInt8Bit.CreateReference

## -description
Returns an [IMemoryBufferReference](../windows.foundation/imemorybufferreference.md) representation of the buffer backing the 8-bit signed integer tensor object.

## -returns
The [IMemoryBufferReference](../windows.foundation/imemorybufferreference.md) representation of a tensor buffer.

## -remarks
All [IMemoryBufferReference](../windows.foundation/imemorybufferreference.md) objects produced by this method must be closed prior to the 8-bit signed integer tensor object's evaluation.

Outstanding [IMemoryBufferReference](../windows.foundation/imemorybufferreference.md) objects are an indication to the engine that the underlying buffer is currently being modified via the **IMemoryBufferByteAccess** native interop interface, and is not ready for evaluation.

## -see-also

## -examples
