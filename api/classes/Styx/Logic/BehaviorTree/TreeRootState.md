# TreeRootState Enumeration

State machine for TreeRoot lifecycle — matches HB 6.2.3. Prevents race conditions between UI thread (Stop) and worker thread (Tick).

## Namespace
[Styx.Logic.BehaviorTree](../../../../namespaces/Styx/Logic/BehaviorTree.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum TreeRootState
```

The TreeRootState type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [TreeRootState](TreeRootState/Constructors/Constructor_F7F2AF830F47.md) | Initializes a new instance of the TreeRootState enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Paused](TreeRootState/Fields/Paused_B8573B18BF59.md) | Represents the paused value. |
| Public field | [Running](TreeRootState/Fields/Running_0C3B5D0257F3.md) | Represents the running value. |
| Public field | [Starting](TreeRootState/Fields/Starting_FA1A66F8A720.md) | Represents the starting value. |
| Public field | [Stopped](TreeRootState/Fields/Stopped_517609014176.md) | Represents the stopped value. |
| Public field | [Stopping](TreeRootState/Fields/Stopping_3EC60375A87B.md) | Represents the stopping value. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | CompareTo(object) | Compares the current instance with another object. (Inherited from Enum.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().). (Inherited from Enum.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().). (Inherited from Enum.) |
| Public method | GetTypeCode | Gets the type code. (Inherited from Enum.) |
| Public method | HasFlag(Enum) | Determines whether has flag. (Inherited from Enum.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides ValueType.ToString().). (Inherited from Enum.) |
| Public method | ToString(string) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(string, IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.BehaviorTree Namespace](../../../../namespaces/Styx/Logic/BehaviorTree.md)
