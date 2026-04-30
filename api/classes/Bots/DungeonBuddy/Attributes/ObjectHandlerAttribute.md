# ObjectHandlerAttribute Class

Marque une méthode comme handler pour un GameObject spécifique. Utilisé pour interagir avec des objets du donjon (leviers, portes, etc.)

## Inheritance Hierarchy
System.Object
  System.Attribute
    Bots.DungeonBuddy.Attributes.ObjectHandlerAttribute

## Namespace
[Bots.DungeonBuddy.Attributes](../../../../namespaces/Bots/DungeonBuddy/Attributes.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed class ObjectHandlerAttribute : Attribute
```

The ObjectHandlerAttribute type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ObjectHandlerAttribute(int)](ObjectHandlerAttribute/Constructors/Constructor_6DADF384654B.md) | Initializes a new instance of the ObjectHandlerAttribute class. |
| Public constructor | [ObjectHandlerAttribute(int, string)](ObjectHandlerAttribute/Constructors/Constructor_7EA08D21E2EF.md) | Initializes a new instance of the ObjectHandlerAttribute class. |
| Public constructor | [ObjectHandlerAttribute(int, string, int)](ObjectHandlerAttribute/Constructors/Constructor_FDAFAA92F17A.md) | Initializes a new instance of the ObjectHandlerAttribute class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ObjectEntry](ObjectHandlerAttribute/Properties/ObjectEntry_946FFFB640B2.md) | Gets or sets the object entry. |
| Public property | [ObjectName](ObjectHandlerAttribute/Properties/ObjectName_68FB7EA9C5C8.md) | Gets or sets the object name. |
| Public property | [ObjectRange](ObjectHandlerAttribute/Properties/ObjectRange_3E29F97AA616.md) | Gets or sets the object range. |
| Public property | [ObjectRangeSqr](ObjectHandlerAttribute/Properties/ObjectRangeSqr_A3CC9A08F0A5.md) | Gets the object range sqr. |
| Public property | TypeId | Gets the type id. (Inherited from Attribute.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from Attribute.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from Attribute.) |
| Public method | IsDefaultAttribute | Determines whether is default attribute. (Inherited from Attribute.) |
| Public method | Match(object) | Determines whether the attribute matches the specified object. (Inherited from Attribute.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Attributes Namespace](../../../../namespaces/Bots/DungeonBuddy/Attributes.md)
