# WaitGetTimeoutDelegate Delegate

Represents a delegate for wait get timeout.

## Namespace
[TreeSharp](../../namespaces/TreeSharp.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed delegate WaitGetTimeoutDelegate
```

The WaitGetTimeoutDelegate type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WaitGetTimeoutDelegate(object, nint)](WaitGetTimeoutDelegate/Constructors/Constructor_4C7B1ABBBC46.md) | Initializes a new instance of the WaitGetTimeoutDelegate delegate. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | HasSingleTarget | Gets a value indicating whether has single target. (Inherited from Delegate.) |
| Public property | Method | Gets the method. (Inherited from Delegate.) |
| Public property | Target | Gets the target. (Inherited from Delegate.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [BeginInvoke(AsyncCallback, object)](WaitGetTimeoutDelegate/Methods/BeginInvoke_84D2C5A3BBEB.md) | Begins asynchronous invocation of the delegate. |
| Public method | [EndInvoke(IAsyncResult)](WaitGetTimeoutDelegate/Methods/EndInvoke_773561E39A3D.md) | Completes asynchronous invocation of the delegate. |
| Protected method | CombineImpl(Delegate) | Combines delegates. (Overrides Delegate.CombineImpl().). (Inherited from MulticastDelegate.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides Delegate.Equals().). (Inherited from MulticastDelegate.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides Delegate.GetHashCode().). (Inherited from MulticastDelegate.) |
| Public method | GetInvocationList | Gets the invocation list. (Overrides Delegate.GetInvocationList().). (Inherited from MulticastDelegate.) |
| Protected method | GetMethodImpl | Gets the method impl. (Overrides Delegate.GetMethodImpl().). (Inherited from MulticastDelegate.) |
| Public method | GetObjectData(SerializationInfo, StreamingContext) | Gets the object data. (Overrides Delegate.GetObjectData().). (Inherited from MulticastDelegate.) |
| Protected method | RemoveImpl(Delegate) | Removes a delegate from the invocation list. (Overrides Delegate.RemoveImpl().). (Inherited from MulticastDelegate.) |
| Public method | Clone | Creates a copy of the current delegate. (Inherited from Delegate.) |
| Public method | DynamicInvoke(object[]) | Dynamically invokes the delegate. (Inherited from Delegate.) |
| Protected method | DynamicInvokeImpl(object[]) | Performs the dynamic delegate invocation. (Inherited from Delegate.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[TreeSharp Namespace](../../namespaces/TreeSharp.md)
