# WhileNode Class

Represents a while node.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.OrderNode
    Styx.Logic.Profiles.Quest.WhileNode

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WhileNode : OrderNode, INodeContainer
```

The WhileNode type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WhileNode(Func<bool>, IEnumerable<OrderNode>)](WhileNode/Constructors/Constructor_507EB7C59D7F.md) | Initializes a new instance of the WhileNode class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Body](WhileNode/Properties/Body_2A4BA34E9040.md) | Gets the body. |
| Public property | [Condition](WhileNode/Properties/Condition_0EECE50331E4.md) | Gets the condition. |
| Public property | [Element](OrderNode/Properties/Element_BBBA08D80255.md) | Gets or sets the element. (Inherited from OrderNode.) |
| Public property | [Type](OrderNode/Properties/Type_BCA153818596.md) | Gets the type. (Inherited from OrderNode.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromXml(XElement)](WhileNode/Methods/FromXml_2D09B07B421B.md) | Creates the instance from XML. |
| Public method | [GetNodes](WhileNode/Methods/GetNodes_718E89DC545A.md) | Gets the nodes. |
| Public method | [ToString](WhileNode/Methods/ToString_67228BD190D3.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
