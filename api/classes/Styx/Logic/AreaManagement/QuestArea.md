# QuestArea Class

Represents a quest area with dynamic hotspot generation.

## Inheritance Hierarchy
System.Object
  Styx.Logic.AreaManagement.Area
    Styx.Logic.AreaManagement.GrindArea
      Styx.Logic.AreaManagement.QuestArea

## Namespace
[Styx.Logic.AreaManagement](../../../../namespaces/Styx/Logic/AreaManagement.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class QuestArea : GrindArea
```

The QuestArea type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestArea(PlayerQuest, IList<WoWQuestStep>)](QuestArea/Constructors/Constructor_F17B6CFBE6AF.md) | Initializes a new instance of the QuestArea class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AreaDefinitions](QuestArea/Properties/AreaDefinitions_2250DE6B7C95.md) | Gets the area definitions. |
| Public property | [HotspotsCreated](QuestArea/Properties/HotspotsCreated_EAD6A51F5938.md) | Gets whether hotspots have been created. |
| Public property | [Quest](QuestArea/Properties/Quest_35713062C100.md) | Gets the associated quest. |
| Public property | [Type](QuestArea/Properties/Type_A3BC1F390C88.md) | Gets the area type. (Overrides GrindArea.Type.) |
| Public property | [CurrentHotSpot](GrindArea/Properties/CurrentHotSpot_88BB82D38345.md) | Gets the current hot spot. (Inherited from GrindArea.) |
| Public property | [Factions](GrindArea/Properties/Factions_AC2BBB9CDB9A.md) | Gets or sets the factions. (Inherited from GrindArea.) |
| Public property | [HotspotChanged](GrindArea/Properties/HotspotChanged_3DC800256733.md) | Gets a value indicating whether hotspot changed. (Inherited from GrindArea.) |
| Public property | [LastHotSpot](GrindArea/Properties/LastHotSpot_532E92D3C8D8.md) | Gets or sets the last hot spot. (Inherited from GrindArea.) |
| Public property | [LootRadius](GrindArea/Properties/LootRadius_F4327BD7B259.md) | Gets or sets the loot radius. (Inherited from GrindArea.) |
| Public property | [MaxDistance](GrindArea/Properties/MaxDistance_0392B994A8EC.md) | Gets or sets the max distance. (Inherited from GrindArea.) |
| Public property | [MaximumHotspotTime](GrindArea/Properties/MaximumHotspotTime_A1C0527B0F17.md) | Gets or sets the maximum hotspot time. (Inherited from GrindArea.) |
| Public property | [MobIDs](GrindArea/Properties/MobIDs_21412AA45EB2.md) | Gets or sets the mob i ds. (Inherited from GrindArea.) |
| Public property | [Name](GrindArea/Properties/Name_01A17720B7EA.md) | Gets or sets the name. (Inherited from GrindArea.) |
| Public property | [RandomizeHotspots](GrindArea/Properties/RandomizeHotspots_6A638434763F.md) | Gets or sets a value indicating whether randomize hotspots. (Inherited from GrindArea.) |
| Public property | [TargetMaxLevel](GrindArea/Properties/TargetMaxLevel_F1EE9DD581D4.md) | Gets or sets the target max level. (Inherited from GrindArea.) |
| Public property | [TargetMinLevel](GrindArea/Properties/TargetMinLevel_D790897BE774.md) | Gets or sets the target min level. (Inherited from GrindArea.) |
| Public property | [CircledHotspots](Area/Properties/CircledHotspots_92168F29FFF8.md) | Gets or sets the circled hotspots. (Inherited from Area.) |
| Public property | [Guid](Area/Properties/Guid_7400E53BA5F5.md) | Gets the guid. (Inherited from Area.) |
| Public property | [Hotspots](Area/Properties/Hotspots_CAB80FE74FF6.md) | Gets or sets the hotspots. (Inherited from Area.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CreateHotspots](QuestArea/Methods/CreateHotspots_26BA0B218664.md) | Creates hotspots from the quest area definitions. |
| Public method | [ToString](GrindArea/Methods/ToString_BC64406225B6.md) | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from GrindArea.) |
| Public method | [CycleToNearest](Area/Methods/CycleToNearest_0E714372D287.md) | Cycles to the nearest hotspot. (Inherited from Area.) |
| Public method | [Equals(Area)](Area/Methods/Equals_1D9675AEB03C.md) | Determines whether the specified object is equal to the current object. (Inherited from Area.) |
| Public method | [Equals(object)](Area/Methods/Equals_FF99EF6C2FAF.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from Area.) |
| Public method | [GetHashCode](Area/Methods/GetHashCode_98F42792A260.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from Area.) |
| Public method | [GetNextHotspot](Area/Methods/GetNextHotspot_B591D7B44C12.md) | Gets the next hotspot. (Inherited from Area.) |
| Public method | [GetRandomHotspot](Area/Methods/GetRandomHotspot_C799D92B1FB0.md) | Gets the random hotspot. (Inherited from Area.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.AreaManagement Namespace](../../../../namespaces/Styx/Logic/AreaManagement.md)
