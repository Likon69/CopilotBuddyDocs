# ProfileTagExpectedException<T> Class

Exception thrown when a profile tag has an unexpected value (generic version with type info).

## Inheritance Hierarchy
System.Object
  System.Exception
    Styx.Logic.Profiles.ProfileException
      Styx.Logic.Profiles.ProfileTagExpectedException<T>

## Namespace
[Styx.Logic.Profiles](../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ProfileTagExpectedException<T> : ProfileException
```

The ProfileTagExpectedException<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ProfileTagExpectedException(XElement)](ProfileTagExpectedException_1/Constructors/Constructor_1EFFE4E37C6E.md) | Initializes a new instance of the ProfileTagExpectedException<T> class. |
| Public constructor | [ProfileTagExpectedException(XElement, string[])](ProfileTagExpectedException_1/Constructors/Constructor_7CAF0CECEC15.md) | Initializes a new instance of the ProfileTagExpectedException<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | Data | Gets the data. (Inherited from Exception.) |
| Public property | HResult | Gets or sets the h result. (Inherited from Exception.) |
| Public property | HelpLink | Gets or sets the help link. (Inherited from Exception.) |
| Public property | InnerException | Gets the inner exception. (Inherited from Exception.) |
| Public property | Message | Gets the message. (Inherited from Exception.) |
| Public property | Source | Gets or sets the source. (Inherited from Exception.) |
| Public property | StackTrace | Gets the stack trace. (Inherited from Exception.) |
| Public property | TargetSite | Gets the target site. (Inherited from Exception.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Protected event | SerializeObjectState | Occurs when serialize object state. (Inherited from Exception.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | GetBaseException | Gets the base exception. (Inherited from Exception.) |
| Public method | GetObjectData(SerializationInfo, StreamingContext) | Gets the object data. (Inherited from Exception.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from Exception.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from Exception.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles Namespace](../../../../namespaces/Styx/Logic/Profiles.md)
