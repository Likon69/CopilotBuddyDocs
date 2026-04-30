# IfNode Class

Represents an if node.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.OrderNode
    Styx.Logic.Profiles.Quest.IfNode

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class IfNode : OrderNode, INodeContainer
```

The IfNode type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [IfNode(Func<bool>, IEnumerable<OrderNode>)](IfNode/Constructors/Constructor_F2D16CCE7744.md) | Initializes a new instance of the IfNode class. |
| Public constructor | [IfNode(Func<bool>, IEnumerable<OrderNode>, IEnumerable<ElseIf>)](IfNode/Constructors/Constructor_853F16BA53A7.md) | Initializes a new instance of the IfNode class. |
| Public constructor | [IfNode(Func<bool>, IEnumerable<OrderNode>, Else)](IfNode/Constructors/Constructor_DDD03B3E3BD9.md) | Initializes a new instance of the IfNode class. |
| Public constructor | [IfNode(Func<bool>, IEnumerable<OrderNode>, IEnumerable<ElseIf>, Else)](IfNode/Constructors/Constructor_384C9695EAC2.md) | Initializes a new instance of the IfNode class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Body](IfNode/Properties/Body_B61C14BA5FB2.md) | Gets the body. |
| Public property | [Condition](IfNode/Properties/Condition_554868ABD323.md) | Gets the condition. |
| Public property | [Else](IfNode/Properties/Else_9B2A9078BC82.md) | Gets the else. |
| Public property | [ElseIfs](IfNode/Properties/ElseIfs_7D91F7AECE46.md) | Gets the else ifs. |
| Public property | Element | Gets or sets the element. (Inherited from OrderNode.) |
| Public property | Type | Gets the type. (Inherited from OrderNode.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromXml(XElement)](IfNode/Methods/FromXml_60B1A51DED84.md) | Creates the instance from XML. |
| Public method | [GetNodes](IfNode/Methods/GetNodes_64F93BDBAC62.md) | Gets the nodes. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
