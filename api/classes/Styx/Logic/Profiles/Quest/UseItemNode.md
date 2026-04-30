# UseItemNode Class

Represents a use item node.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.OrderNode
    Styx.Logic.Profiles.Quest.UseItemNode

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class UseItemNode : OrderNode
```

The UseItemNode type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [UseItemNode.UseItemTargetType](UseItemNode/UseItemTargetType.md) | Represents values for Use Item Target Type. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [UseItemNode(Func<WoWItem>, uint, WoWPoint)](UseItemNode/Constructors/Constructor_59B151743FA0.md) | Initializes a new instance of the UseItemNode class. |
| Public constructor | [UseItemNode(Func<WoWItem>, Func<WoWObject>, uint, WoWPoint)](UseItemNode/Constructors/Constructor_699A3FEDEBE1.md) | Initializes a new instance of the UseItemNode class. |
| Public constructor | [UseItemNode(Func<WoWItem>, Func<WoWObject>, UseItemTargetType, bool, uint, WoWPoint)](UseItemNode/Constructors/Constructor_6F91332278F7.md) | Initializes a new instance of the UseItemNode class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ForceUse](UseItemNode/Properties/ForceUse_49B2DAEC4CA3.md) | Gets a value indicating whether force use. |
| Public property | [ItemRetriever](UseItemNode/Properties/ItemRetriever_3CDEC24C8562.md) | Gets the item retriever. |
| Public property | [Location](UseItemNode/Properties/Location_9857C6CD2B0E.md) | Gets the location. |
| Public property | [QuestId](UseItemNode/Properties/QuestId_34CCA82228D7.md) | Gets the quest id. |
| Public property | [TargetRetriever](UseItemNode/Properties/TargetRetriever_AE6A044647D3.md) | Gets the target retriever. |
| Public property | [TargetType](UseItemNode/Properties/TargetType_A7FFACF0E6A9.md) | Gets the target type. |
| Public property | [Element](OrderNode/Properties/Element_BBBA08D80255.md) | Gets or sets the element. (Inherited from OrderNode.) |
| Public property | [Type](OrderNode/Properties/Type_BCA153818596.md) | Gets the type. (Inherited from OrderNode.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromXml(XElement)](UseItemNode/Methods/FromXml_A9B3DC602323.md) | Creates the instance from XML. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
