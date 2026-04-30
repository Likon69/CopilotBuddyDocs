# FrameLock Class

Acquires continuous execution mode on the EndScene executor for the duration of its lifetime. While held, every call reuses the same hooked frame instead of waiting for a new one. Ported from HB 5.4.8/6.2.3 GreyMagic.FrameLock design: - Per-instance tracking via _wasAcquired (no static counter) - Exception-safe - Full IDisposable pattern with finalizer safety - _disposed guard prevents double-dispose Keeps a parameterless constructor (all call sites use new FrameLock()) and resolves the executor via .

## Inheritance Hierarchy
System.Object
  Styx.FrameLock

## Namespace
[Styx](../../namespaces/Styx.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class FrameLock : IDisposable
```

The FrameLock type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [FrameLock](FrameLock/Constructors/Constructor_692F43614D3A.md) | Initializes a new instance of the FrameLock class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Executor](FrameLock/Properties/Executor_62CC1184F2FB.md) | The executor this lock is bound to. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Dispose](FrameLock/Methods/Dispose_C70F7C517C8D.md) | Releases the resources used by the instance. |
| Protected method | [Dispose(bool)](FrameLock/Methods/Dispose_AE16525B1ABA.md) | Releases the resources used by the instance. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx Namespace](../../namespaces/Styx.md)
