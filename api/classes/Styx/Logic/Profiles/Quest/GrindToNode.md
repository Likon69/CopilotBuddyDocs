# GrindToNode Class

Node for grinding to a specific level.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.OrderNode
    Styx.Logic.Profiles.Quest.GrindToNode

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GrindToNode : OrderNode
```

The GrindToNode type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GrindToNode(float)](GrindToNode/Constructors/Constructor_5D55FF2862CC.md) | Initializes a new instance of the GrindToNode class. |
| Public constructor | [GrindToNode(float, Func<bool>)](GrindToNode/Constructors/Constructor_94EF14FB7A3D.md) | Initializes a new instance of the GrindToNode class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Condition](GrindToNode/Properties/Condition_90D53BB0586F.md) | Condition function for grinding. |
| Public property | [GoalText](GrindToNode/Properties/GoalText_34D57533E441.md) | Goal text to display while grinding. |
| Public property | [Level](GrindToNode/Properties/Level_9BF830C2CE11.md) | Target level to grind to. |
| Public property | Element | Gets or sets the element. (Inherited from OrderNode.) |
| Public property | Type | Gets the type. (Inherited from OrderNode.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromXml(XElement)](GrindToNode/Methods/FromXml_D407B76CA719.md) | Creates the instance from XML. |
| Public method | [ToString](GrindToNode/Methods/ToString_623EF8AEC3AF.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
