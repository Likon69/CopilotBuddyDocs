# BossManager.Boss Class

Represents a dungeon boss definition.

## Inheritance Hierarchy
System.Object
  Bots.DungeonBuddy.BossManager.Boss

## Namespace
[Bots.DungeonBuddy](../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class BossManager.Boss
```

The BossManager.Boss type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Boss](Boss/Constructors/Constructor_EC9A177A43E7.md) | Initializes a new instance of the BossManager.Boss class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CastingSpellId](Boss/Properties/CastingSpellId_7C99214F936A.md) | Gets or sets the casting spell id. |
| Public property | [Entry](Boss/Properties/Entry_DF2302DE54B2.md) | Gets or sets the entry. |
| Public property | [EntryId](Boss/Properties/EntryId_BE95C84A4A97.md) | Gets or sets the entry id. |
| Public property | [IsAlive](Boss/Properties/IsAlive_5FB085905FDC.md) | Gets a value indicating whether is alive. |
| Public property | [IsDead](Boss/Properties/IsDead_CCEF2EF5AEA9.md) | Gets or sets a value indicating whether is dead. |
| Public property | [IsOptional](Boss/Properties/IsOptional_BC28A35551A1.md) | Gets or sets a value indicating whether is optional. |
| Public property | [Location](Boss/Properties/Location_60D497A65FE6.md) | Best-effort world location: uses live ObjectManager unit if in range, otherwise WoWPoint.Zero. Callers should guard for Zero. |
| Public property | [Name](Boss/Properties/Name_A95C898FE19D.md) | Gets or sets the name. |
| Public property | [Optional](Boss/Properties/Optional_2A1B2A0C45D0.md) | Gets or sets a value indicating whether optional. |
| Public property | [PathBreadCrumbs](Boss/Properties/PathBreadCrumbs_7A335064AC90.md) | Gets or sets the path bread crumbs. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [MarkAsDead](Boss/Methods/MarkAsDead_CE8C7B6DCE55.md) | Marks this boss as dead. Called by dungeon scripts (HB Boss.MarkAsDead() parity). |
| Public method | [Reset](Boss/Methods/Reset_37B54D6B7F03.md) | Resets this boss to alive. Called by BossManager.Reset(). |
| Public method | [ToWoWUnit](Boss/Methods/ToWoWUnit_2BFCA79177EA.md) | Converts to wow unit. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy Namespace](../../../../namespaces/Bots/DungeonBuddy.md)
