# EncounterHandlerAttribute Class

Marque une méthode comme handler pour un boss spécifique. La méthode doit retourner un Composite (behavior tree).

## Inheritance Hierarchy
System.Object
  System.Attribute
    Bots.DungeonBuddy.Attributes.EncounterHandlerAttribute

## Namespace
[Bots.DungeonBuddy.Attributes](../../../../namespaces/Bots/DungeonBuddy/Attributes.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed class EncounterHandlerAttribute : Attribute
```

The EncounterHandlerAttribute type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [EncounterHandlerAttribute(int)](EncounterHandlerAttribute/Constructors/Constructor_AE384CAA9FC7.md) | Initializes a new instance of the EncounterHandlerAttribute class. |
| Public constructor | [EncounterHandlerAttribute(int, string)](EncounterHandlerAttribute/Constructors/Constructor_16F50A4EAA66.md) | Initializes a new instance of the EncounterHandlerAttribute class. |
| Public constructor | [EncounterHandlerAttribute(int, string, CallBehaviorMode)](EncounterHandlerAttribute/Constructors/Constructor_4CF23038FCBC.md) | Initializes a new instance of the EncounterHandlerAttribute class. |
| Public constructor | [EncounterHandlerAttribute(int, string, int, CallBehaviorMode)](EncounterHandlerAttribute/Constructors/Constructor_8E4D8630F55E.md) | Initializes a new instance of the EncounterHandlerAttribute class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BossEntry](EncounterHandlerAttribute/Properties/BossEntry_0FADBA36143D.md) | Entry ID du boss (from creature_template) |
| Public property | [BossName](EncounterHandlerAttribute/Properties/BossName_90D936D29CBE.md) | Nom d'affichage du boss |
| Public property | [BossRange](EncounterHandlerAttribute/Properties/BossRange_485D3DA3502A.md) | Distance de détection du boss (yards) |
| Public property | [BossRangeSqr](EncounterHandlerAttribute/Properties/BossRangeSqr_2101E0DCC709.md) | Gets the boss range sqr. |
| Public property | [Mode](EncounterHandlerAttribute/Properties/Mode_5E50FB2265CF.md) | Mode d'appel du behavior |
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
