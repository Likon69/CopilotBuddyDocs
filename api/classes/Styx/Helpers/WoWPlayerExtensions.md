# WoWPlayerExtensions Class

Extension methods pour WoWPlayer/LocalPlayer. Permet d'appeler IsTank(), IsDps(), IsHealer() comme méthodes (les scripts DungeonBuddy les appellent avec parenthèses). Compatible HB 4.3.4 qui avait ces méthodes. IMPORTANT: Ces méthodes utilisent UnitGroupRolesAssigned() pour détecter le rôle LFG ASSIGNÉ, pas la classe du joueur. Un Paladin Holy ne doit PAS retourner IsTank()=true. Les properties WoWPlayer.IsTank/IsHealer (class-based) restent disponibles pour savoir si la classe PEUT jouer ce rôle. Référence HB 4.3.4: ScriptHelpers.cs L1308-L1501

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class WoWPlayerExtensions
```

The WoWPlayerExtensions type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [IsDps(WoWPlayer)](WoWPlayerExtensions/Methods/IsDps_F56C423137F7.md) | True si le joueur a le rôle DPS (DAMAGER) assigné. |
| Public method Static member | [IsFollower(WoWPlayer)](WoWPlayerExtensions/Methods/IsFollower_47065B4711D4.md) | Determines whether is follower. |
| Public method Static member | [IsHealer(WoWPlayer)](WoWPlayerExtensions/Methods/IsHealer_180A2C89A8DB.md) | True si le joueur a le rôle HEALER assigné dans le LFG/groupe. |
| Public method Static member | [IsLeader(WoWPlayer)](WoWPlayerExtensions/Methods/IsLeader_CB62EACD74EB.md) | Determines whether is leader. |
| Public method Static member | [IsMelee(WoWPlayer)](WoWPlayerExtensions/Methods/IsMelee_4AF601020A4E.md) | Determines whether is melee. |
| Public method Static member | [IsRange(WoWPlayer)](WoWPlayerExtensions/Methods/IsRange_5F32608E17E6.md) | Determines whether is range. |
| Public method Static member | [IsTank(WoWPlayer)](WoWPlayerExtensions/Methods/IsTank_E0F979098EBD.md) | True si le joueur a le rôle TANK assigné dans le LFG/groupe. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
