# Dungeon Class

Classe de base pour tous les scripts de donjon. Chaque donjon hérite de cette classe.

## Inheritance Hierarchy
System.Object
  Bots.DungeonBuddy.Dungeon

## Namespace
[Bots.DungeonBuddy](../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class Dungeon : IDisposable
```

The Dungeon type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [Dungeon](Dungeon/Constructors/Constructor_247E1894CB4A.md) | Initializes a new instance of the Dungeon class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CorpseRunBreadCrumb](Dungeon/Properties/CorpseRunBreadCrumb_797BC9B49473.md) | Gets the corpse run bread crumb. |
| Public property | [DungeonId](Dungeon/Properties/DungeonId_4DE5EE865F49.md) | ID du donjon dans LFG_Dungeons.dbc |
| Public property | [Entrance](Dungeon/Properties/Entrance_EF8449232F1B.md) | Gets the entrance. |
| Public property | [ExitLocation](Dungeon/Properties/ExitLocation_54330BBCB065.md) | Position de la sortie du donjon |
| Public property | [IsComplete](Dungeon/Properties/IsComplete_7E1EEA1A0EFF.md) | True si le donjon est terminé (tous les boss tués) |
| Public property | [IsFlyingCorpseRun](Dungeon/Properties/IsFlyingCorpseRun_1B2DE214E8D2.md) | True si le corpse run peut se faire en volant |
| Public property | [Name](Dungeon/Properties/Name_6CAF0CC85F04.md) | Nom du donjon (affiché depuis LFG_Dungeons.dbc) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [AddAvoid(AvoidInfo)](Dungeon/Methods/AddAvoid_B8716E910D4F.md) | Adds the avoid. |
| Protected method | [AddAvoidRange(IEnumerable<AvoidInfo>)](Dungeon/Methods/AddAvoidRange_4E7890AA7C2A.md) | Adds the avoid range. |
| Protected method | [ClearAvoids](Dungeon/Methods/ClearAvoids_221519F3A883.md) | Clears registered avoids. |
| Public method | [Dispose](Dungeon/Methods/Dispose_49E6B79D054F.md) | Releases the resources used by the instance. |
| Protected method | [Finalize](Dungeon/Methods/Finalize_AF90E224E046.md) | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. |
| Public method | [IncludeTargetsFilter(List<WoWObject>, HashSet<WoWObject>)](Dungeon/Methods/IncludeTargetsFilter_096A19D92ACF.md) | Filtre de ciblage: Ajouter des cibles |
| Public method | [MoveTo(WoWPoint)](Dungeon/Methods/MoveTo_511FD34FB973.md) | Moves to to. |
| Public method | [OnEnter](Dungeon/Methods/OnEnter_9E2A819E870B.md) | Override pour logique d'entrée custom |
| Public method | [OnExit](Dungeon/Methods/OnExit_711E80F74626.md) | Override pour logique de sortie custom |
| Protected method | [RemoveAvoid(AvoidInfo)](Dungeon/Methods/RemoveAvoid_2FD354F7C8E2.md) | Removes the avoid. |
| Public method | [RemoveTargetsFilter(List<WoWObject>)](Dungeon/Methods/RemoveTargetsFilter_62FD37D10590.md) | Filtre de ciblage: Retirer des cibles |
| Public method | [WeighTargetsFilter(List<TargetPriority>)](Dungeon/Methods/WeighTargetsFilter_5F9188716F21.md) | Filtre de ciblage: Modifier les priorités |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy Namespace](../../../namespaces/Bots/DungeonBuddy.md)
