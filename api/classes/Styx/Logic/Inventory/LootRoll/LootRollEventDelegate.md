# LootRoll.LootRollEventDelegate Delegate

Delegate for loot roll events.

## Namespace
[Styx.Logic.Inventory](../../../../../namespaces/Styx/Logic/Inventory.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed delegate LootRoll.LootRollEventDelegate
```

The LootRoll.LootRollEventDelegate type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LootRollEventDelegate(object, nint)](LootRollEventDelegate/Constructors/Constructor_06780CC71EB1.md) | Initializes a new instance of the LootRoll.LootRollEventDelegate delegate. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | HasSingleTarget | Gets a value indicating whether has single target. (Inherited from Delegate.) |
| Public property | Method | Gets the method. (Inherited from Delegate.) |
| Public property | Target | Gets the target. (Inherited from Delegate.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [BeginInvoke(LootRollItemInfo, AsyncCallback, object)](LootRollEventDelegate/Methods/BeginInvoke_328DCA3F56F7.md) | Begins asynchronous invocation of the delegate. |
| Public method | [EndInvoke(IAsyncResult)](LootRollEventDelegate/Methods/EndInvoke_E8712CE2A00B.md) | Completes asynchronous invocation of the delegate. |
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
[Styx.Logic.Inventory Namespace](../../../../../namespaces/Styx/Logic/Inventory.md)
