# ScriptHelpers Class

Helpers pour écrire les scripts de donjons. Utilisés avec [EncounterHandler] et [ObjectHandler]. NOTE: Requiert WoWPlayerExtensions.cs pour IsTank()/IsDps()/IsHealer()

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class ScriptHelpers
```

The ScriptHelpers type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [ScriptHelpers.EnemyDispellType](ScriptHelpers/EnemyDispellType.md) | Represents values for Enemy Dispell Type. |
| Public enumeration | [ScriptHelpers.PartyRole](ScriptHelpers/PartyRole.md) | Represents values for Party Role. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CurrentBoss](ScriptHelpers/Properties/CurrentBoss_7CE670633721.md) | Gets the current boss. |
| Public property Static member | [EventInProcess](ScriptHelpers/Properties/EventInProcess_624050A39E74.md) | True si un event de script est en cours (RP, cinématique, etc.) |
| Public property Static member | [Healer](ScriptHelpers/Properties/Healer_F3A8F7C7436B.md) | Le joueur est le healer du groupe |
| Public property Static member | [MovementEnabled](ScriptHelpers/Properties/MovementEnabled_4B23B521105F.md) | Gets a value indicating whether movement enabled. |
| Public property Static member | [MyRole](ScriptHelpers/Properties/MyRole_7DFF8F3C3A9C.md) | Obtient le rôle du joueur actuel |
| Public property Static member | [PartyIncludingMe](ScriptHelpers/Properties/PartyIncludingMe_8F97139E6DD0.md) | Tous les membres du groupe/raid, moi inclus. Utilisé par Violet Hold x2. |
| Public property Static member | [Tank](ScriptHelpers/Properties/Tank_20D6D385A5EF.md) | Le joueur est le tank du groupe |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [BuyItem(uint, int)](ScriptHelpers/Methods/BuyItem_AAA5A5A1A670.md) | Buys the item. |
| Public method Static member | [ControlledMoveTo(Func<WoWPoint>)](ScriptHelpers/Methods/ControlledMoveTo_128E4D755D6A.md) | Moves to the controlled destination. |
| Public method Static member | [ControlledMoveTo(WoWPoint)](ScriptHelpers/Methods/ControlledMoveTo_6B7BD74F199D.md) | Moves to the controlled destination. |
| Public method Static member | [CreateCastRangedAbility](ScriptHelpers/Methods/CreateCastRangedAbility_3A8329450D56.md) | Creates the cast ranged ability. |
| Public method Static member | [CreateCastRangedAbility(string, Func<WoWUnit>)](ScriptHelpers/Methods/CreateCastRangedAbility_C5C2445F782F.md) | Creates the cast ranged ability. |
| Public method Static member | [CreateCastRangedAbility(CanRunDecoratorDelegate, string, Func<WoWUnit>)](ScriptHelpers/Methods/CreateCastRangedAbility_E7CBD84866CC.md) | Creates the cast ranged ability. |
| Public method Static member | [CreateClearArea(Func<WoWPoint>, float, Func<WoWUnit, bool>)](ScriptHelpers/Methods/CreateClearArea_4284154AE5BC.md) | Tue les PNJ hostiles dans un rayon autour d'une position. Référence HB 4.3.4 ScriptHelpers.cs L395 |
| Public method Static member | [CreateDispellEnemy(string, EnemyDispellType, Func<WoWUnit>)](ScriptHelpers/Methods/CreateDispellEnemy_5C3BD9899155.md) | Dispel un buff enemy |
| Public method Static member | [CreateForceJump(CanRunDecoratorDelegate, Func<WoWPoint>, Func<WoWPoint>)](ScriptHelpers/Methods/CreateForceJump_5A0E01F68520.md) | Creates the force jump. |
| Public method Static member | [CreateForceJump(CanRunDecoratorDelegate, WoWPoint, WoWPoint)](ScriptHelpers/Methods/CreateForceJump_89489F6819EB.md) | Creates the force jump. |
| Public method Static member | [CreateForceJump(CanRunDecoratorDelegate, Func<WoWPoint>, Func<WoWPoint>, int)](ScriptHelpers/Methods/CreateForceJump_314FF4304219.md) | Creates the force jump. |
| Public method Static member | [CreateForceJump(CanRunDecoratorDelegate, bool, WoWPoint, WoWPoint)](ScriptHelpers/Methods/CreateForceJump_EEFE11C73924.md) | Creates the force jump. |
| Public method Static member | [CreateInteractWithObject(uint)](ScriptHelpers/Methods/CreateInteractWithObject_F6D1F74E0412.md) | Creates the interact with object. |
| Public method Static member | [CreateInteractWithObject(Func<WoWGameObject>)](ScriptHelpers/Methods/CreateInteractWithObject_497FAC51C306.md) | Interact avec un GameObject |
| Public method Static member | [CreateInteractWithObject(Func<WoWGameObject>, float)](ScriptHelpers/Methods/CreateInteractWithObject_ED849AB7D180.md) | Creates the interact with object. |
| Public method Static member | [CreateInteractWithObject(uint, float)](ScriptHelpers/Methods/CreateInteractWithObject_D924DAC48E23.md) | Creates the interact with object. |
| Public method Static member | [CreateInteractWithObject(uint, int)](ScriptHelpers/Methods/CreateInteractWithObject_E8C69719D7F9.md) | Creates the interact with object. |
| Public method Static member | [CreateInteractWithObject(uint, int, bool)](ScriptHelpers/Methods/CreateInteractWithObject_0C56DE823158.md) | Creates the interact with object. |
| Public method Static member | [CreateInteractWithObject(Func<WoWGameObject>, float, bool)](ScriptHelpers/Methods/CreateInteractWithObject_CD486ECD3EC6.md) | Overload avec range + ignoreCombat — UP, Nexus, Violet Hold, HoS. |
| Public method Static member | [CreateInteractWithObjectContinue(uint)](ScriptHelpers/Methods/CreateInteractWithObjectContinue_4EE328499A2B.md) | Creates the interact with object continue. |
| Public method Static member | [CreateInteractWithObjectContinue(uint, int)](ScriptHelpers/Methods/CreateInteractWithObjectContinue_A05B47EEF887.md) | Creates the interact with object continue. |
| Public method Static member | [CreateInteractWithObjectContinue(CanRunDecoratorDelegate, Func<WoWGameObject>, float)](ScriptHelpers/Methods/CreateInteractWithObjectContinue_3294EC270904.md) | Creates the interact with object continue. |
| Public method Static member | [CreateInteractWithObjectContinue(uint, int, bool)](ScriptHelpers/Methods/CreateInteractWithObjectContinue_0E51D4E3594A.md) | Creates the interact with object continue. |
| Public method Static member | [CreateJumpDown(CanRunDecoratorDelegate, Func<WoWPoint>)](ScriptHelpers/Methods/CreateJumpDown_4367EDF2EEF8.md) | Creates the jump down. |
| Public method Static member | [CreateJumpDown(CanRunDecoratorDelegate, WoWPoint, WoWPoint)](ScriptHelpers/Methods/CreateJumpDown_B1CEFB5A23AB.md) | Creates the jump down. |
| Public method Static member | [CreateJumpDown(CanRunDecoratorDelegate, bool, WoWPoint, WoWPoint)](ScriptHelpers/Methods/CreateJumpDown_1F67B84C4319.md) | Creates the jump down. |
| Public method Static member | [CreateLosLocation(CanRunDecoratorDelegate, Func<WoWPoint>)](ScriptHelpers/Methods/CreateLosLocation_8AA3B899A1B4.md) | Creates the los location. |
| Public method Static member | [CreateLosLocation(CanRunDecoratorDelegate, Func<WoWPoint>, Func<WoWPoint>, Func<float>)](ScriptHelpers/Methods/CreateLosLocation_8FA563C41EF2.md) | Creates the los location. |
| Public method Static member | [CreateLosLocation(CanRunDecoratorDelegate, Func<WoWUnit>, float, Func<WoWPoint>)](ScriptHelpers/Methods/CreateLosLocation_2BB687613F91.md) | Creates the los location. |
| Public method Static member | [CreateMountBehavior](ScriptHelpers/Methods/CreateMountBehavior_434579741700.md) | Creates the mount behavior. |
| Public method Static member | [CreateMountBehavior(Func<WoWPoint>)](ScriptHelpers/Methods/CreateMountBehavior_16872BD4F164.md) | Creates the mount behavior. |
| Public method Static member | [CreateMountBehavior(CanRunDecoratorDelegate)](ScriptHelpers/Methods/CreateMountBehavior_E2001C372C81.md) | Creates the mount behavior. |
| Public method Static member | [CreateMoveToContinue(uint)](ScriptHelpers/Methods/CreateMoveToContinue_02847D88BF05.md) | Continue à se déplacer vers un objectif (objet ou position). Multiples overloads pour compatibilité avec les scripts. Référence HB 4.3.4 ScriptHelpers.cs L2430-L2490 |
| Public method Static member | [CreateMoveToContinue(Func<WoWObject>)](ScriptHelpers/Methods/CreateMoveToContinue_135AD5AD9D9A.md) | Creates the move to continue. |
| Public method Static member | [CreateMoveToContinue(WoWPoint)](ScriptHelpers/Methods/CreateMoveToContinue_1C1C7C508CDF.md) | Creates the move to continue. |
| Public method Static member | [CreateMoveToContinue(Func<WoWPoint>)](ScriptHelpers/Methods/CreateMoveToContinue_3BF8E71804A8.md) | Creates the move to continue. |
| Public method Static member | [CreateMoveToContinue(CanRunDecoratorDelegate, uint, bool)](ScriptHelpers/Methods/CreateMoveToContinue_78ACDEEFADDE.md) | Creates the move to continue. |
| Public method Static member | [CreateMoveToContinue(CanRunDecoratorDelegate, Func<WoWObject>, bool)](ScriptHelpers/Methods/CreateMoveToContinue_A9CD3E8C5142.md) | Creates the move to continue. |
| Public method Static member | [CreateMoveToContinue(CanRunDecoratorDelegate, Func<WoWPoint>, bool)](ScriptHelpers/Methods/CreateMoveToContinue_4251D3D259DC.md) | Creates the move to continue. |
| Public method Static member | [CreatePickupQuest(uint)](ScriptHelpers/Methods/CreatePickupQuest_8AD2C074ECAE.md) | Creates the pickup quest. |
| Public method Static member | [CreatePickupQuest(uint, int)](ScriptHelpers/Methods/CreatePickupQuest_27FD77E3CC42.md) | Creates the pickup quest. |
| Public method Static member | [CreatePullNpcToLocation(CanRunDecoratorDelegate, Func<WoWUnit>, Func<WoWPoint>, int)](ScriptHelpers/Methods/CreatePullNpcToLocation_AE2E427C9283.md) | Creates the pull npc to location. |
| Public method Static member | [CreatePullNpcToLocation(CanRunDecoratorDelegate, Func<WoWUnit>, Func<WoWPoint>, float)](ScriptHelpers/Methods/CreatePullNpcToLocation_DF23425B35EB.md) | Crée un behavior pour pull trash vers une position |
| Public method Static member | [CreatePullNpcToLocation(CanRunDecoratorDelegate, CanRunDecoratorDelegate, Func<WoWUnit>, Func<WoWPoint>, int)](ScriptHelpers/Methods/CreatePullNpcToLocation_FA8F6F124D0E.md) | Creates the pull npc to location. |
| Public method Static member | [CreatePullNpcToLocation(CanRunDecoratorDelegate, CanRunDecoratorDelegate, Func<WoWUnit>, Func<WoWPoint>, Func<WoWPoint>)](ScriptHelpers/Methods/CreatePullNpcToLocation_27994AAD538D.md) | Creates the pull npc to location. |
| Public method Static member | [CreatePullNpcToLocation(CanRunDecoratorDelegate, CanRunDecoratorDelegate, Func<WoWUnit>, Func<WoWPoint>, Func<WoWPoint>, int)](ScriptHelpers/Methods/CreatePullNpcToLocation_C06B1554B437.md) | Creates the pull npc to location. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, float, uint)](ScriptHelpers/Methods/CreateRunAwayFromBad_1120670223E2.md) | Crée un behavior pour fuir une zone dangereuse |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, float, uint[])](ScriptHelpers/Methods/CreateRunAwayFromBad_76DD24F9CDD3.md) | Overload params uint[] — Violet Hold, DTK, Ahn'kahet. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, float, Predicate<WoWObject>)](ScriptHelpers/Methods/CreateRunAwayFromBad_5DB350F3CCF9.md) | Creates the run away from bad. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, Func<WoWPoint>, float, float, uint)](ScriptHelpers/Methods/CreateRunAwayFromBad_235D6859805E.md) | Overload avec Func center + range + radius + uint — HoL, Gundrak, DTK. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, Func<WoWPoint>, float, float, Predicate<WoWObject>)](ScriptHelpers/Methods/CreateRunAwayFromBad_0020F6139E0C.md) | Overload avec Func center + range + radius + Predicate — DTK Trollgore. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, WoWPoint, float, float, uint)](ScriptHelpers/Methods/CreateRunAwayFromBad_C63758DEC87F.md) | Overload avec WoWPoint direct (pas Func) — Azjol-Nerub, Deadmines. HB 4.3.4: convertit WoWPoint en lambda pour les scripts qui passent le point directement. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, WoWPoint, float, float, uint[])](ScriptHelpers/Methods/CreateRunAwayFromBad_32E69C9C9FBD.md) | Creates the run away from bad. |
| Public method Static member | [CreateRunAwayFromBad(CanRunDecoratorDelegate, WoWPoint, float, float, Predicate<WoWObject>)](ScriptHelpers/Methods/CreateRunAwayFromBad_E8E6D2619C52.md) | Creates the run away from bad. |
| Public method Static member | [CreateRunAwayFromLocation(CanRunDecoratorDelegate, Func<WoWPoint>, float)](ScriptHelpers/Methods/CreateRunAwayFromLocation_7856B48EA188.md) | Creates the run away from location. |
| Public method Static member | [CreateRunAwayFromLocation(CanRunDecoratorDelegate, float, Func<WoWPoint>)](ScriptHelpers/Methods/CreateRunAwayFromLocation_24459D236D08.md) | Creates the run away from location. |
| Public method Static member | [CreateSpreadOutLogic(CanRunDecoratorDelegate, int)](ScriptHelpers/Methods/CreateSpreadOutLogic_B7B28B8D380F.md) | Creates the spread out logic. |
| Public method Static member | [CreateSpreadOutLogic(CanRunDecoratorDelegate, Func<WoWPoint>, int, float)](ScriptHelpers/Methods/CreateSpreadOutLogic_6F1F8010C8AD.md) | Creates the spread out logic. |
| Public method Static member | [CreateTalkToNpc(uint)](ScriptHelpers/Methods/CreateTalkToNpc_A8F3A157A072.md) | Crée un behavior pour parler à un NPC |
| Public method Static member | [CreateTalkToNpcContinue(Func<WoWUnit>)](ScriptHelpers/Methods/CreateTalkToNpcContinue_CD9E8281B577.md) | Creates the talk to npc continue. |
| Public method Static member | [CreateTalkToNpcContinue(uint)](ScriptHelpers/Methods/CreateTalkToNpcContinue_C0FE5A40D640.md) | Creates the talk to npc continue. |
| Public method Static member | [CreateTalkToNpcContinue(CanRunDecoratorDelegate, Func<WoWUnit>)](ScriptHelpers/Methods/CreateTalkToNpcContinue_1B4A6DF7D232.md) | Creates the talk to npc continue. |
| Public method Static member | [CreateTalkToNpcContinue(uint, int)](ScriptHelpers/Methods/CreateTalkToNpcContinue_35571292E38F.md) | Creates the talk to npc continue. |
| Public method Static member | [CreateTankAgainstObject(Func<WoWGameObject>)](ScriptHelpers/Methods/CreateTankAgainstObject_03A789BBCDD3.md) | Creates the tank against object. |
| Public method Static member | [CreateTankAgainstObject(CanRunDecoratorDelegate, Func<WoWGameObject>, float)](ScriptHelpers/Methods/CreateTankAgainstObject_0ABA4DBDD886.md) | Creates the tank against object. |
| Public method Static member | [CreateTankAgainstObject(CanRunDecoratorDelegate, Func<WoWPoint>, Func<float>)](ScriptHelpers/Methods/CreateTankAgainstObject_3CE9B9364ABD.md) | Creates the tank against object. |
| Public method Static member | [CreateTankFaceAwayGroupUnit(float)](ScriptHelpers/Methods/CreateTankFaceAwayGroupUnit_F0BC5B79C85B.md) | Le tank doit faire face away du groupe (pour cleave/breath) |
| Public method Static member | [CreateTankTalkToThenEscortNpc(int, WoWPoint, WoWPoint)](ScriptHelpers/Methods/CreateTankTalkToThenEscortNpc_34C4D2C59261.md) | Creates the tank talk to then escort npc. |
| Public method Static member | [CreateTankTalkToThenEscortNpc(uint, WoWPoint, WoWPoint)](ScriptHelpers/Methods/CreateTankTalkToThenEscortNpc_1E6776F837EE.md) | Escort NPC d'un point A vers un point B |
| Public method Static member | [CreateTankTalkToThenEscortNpc(CanRunDecoratorDelegate, Func<WoWUnit>, float, bool, int, Func<WoWPoint>)](ScriptHelpers/Methods/CreateTankTalkToThenEscortNpc_FDD16D210944.md) | Creates the tank talk to then escort npc. |
| Public method Static member | [CreateTankTalkToThenEscortNpc(int, int, WoWPoint, WoWPoint, float, Func<bool>)](ScriptHelpers/Methods/CreateTankTalkToThenEscortNpc_DB9E339B0641.md) | Creates the tank talk to then escort npc. |
| Public method Static member | [CreateTankUnitAtLocation(Func<WoWPoint>, float)](ScriptHelpers/Methods/CreateTankUnitAtLocation_9DBF22224C5B.md) | Déplace le tank vers une position spécifique. Utilisé par les scripts: HoL, HoL Heroic, etc. Référence HB 4.3.4 ScriptHelpers.cs L2088 |
| Public method Static member | [CreateTurninQuest(uint)](ScriptHelpers/Methods/CreateTurninQuest_43BFE33F0348.md) | Creates the turnin quest. |
| Public method Static member | [CreateTurninQuest(uint, int)](ScriptHelpers/Methods/CreateTurninQuest_319E40DAC8E8.md) | Creates the turnin quest. |
| Public method Static member | [CreateTurninQuest(uint, int, int)](ScriptHelpers/Methods/CreateTurninQuest_DFC57DB2E1A2.md) | Creates the turnin quest. |
| Public method Static member | [CreateWaitAtLocationUntilTankPulled(Func<WoWPoint>)](ScriptHelpers/Methods/CreateWaitAtLocationUntilTankPulled_F78B75BC7FCE.md) | Creates the wait at location until tank pulled. |
| Public method Static member | [CreateWaitAtLocationUntilTankPulled(CanRunDecoratorDelegate, Func<WoWPoint>)](ScriptHelpers/Methods/CreateWaitAtLocationUntilTankPulled_E5743F8E763F.md) | Creates the wait at location until tank pulled. |
| Public method Static member | [CreateWaitAtLocationUntilTankPulled(CanRunDecoratorDelegate, Func<WoWPoint>, float)](ScriptHelpers/Methods/CreateWaitAtLocationUntilTankPulled_B2C1E6F3C6D9.md) | Creates the wait at location until tank pulled. |
| Public method Static member | [Cross(WoWPoint, WoWPoint)](ScriptHelpers/Methods/Cross_B63AF8B8F2A0.md) | Computes the cross product. |
| Public method Static member | [DisableMovement(Func<bool>)](ScriptHelpers/Methods/DisableMovement_70D56C62F7B7.md) | Disables movement. |
| Public method Static member | [Dot(WoWPoint, WoWPoint)](ScriptHelpers/Methods/Dot_3794F02F1E41.md) | Computes the dot product. |
| Public method Static member | [FindBestTargetWithIdsRange(float, uint[])](ScriptHelpers/Methods/FindBestTargetWithIdsRange_189CA8573371.md) | Finds the best target with ids range. |
| Public method Static member | [GetBehindUnit(CanRunDecoratorDelegate, Func<WoWUnit>)](ScriptHelpers/Methods/GetBehindUnit_872D760B2134.md) | Gets the behind unit. |
| Public method Static member | [GetNearestPointOnLine(WoWPoint, WoWPoint, WoWPoint)](ScriptHelpers/Methods/GetNearestPointOnLine_737567FAC6F9.md) | Gets the nearest point on line. |
| Public method Static member | [GetNearestPointOnSegment(WoWPoint, WoWPoint, WoWPoint)](ScriptHelpers/Methods/GetNearestPointOnSegment_3AE7F8FCF04A.md) | Gets the nearest point on segment. |
| Public method Static member | [GetPartyMembersByRole(PartyRole)](ScriptHelpers/Methods/GetPartyMembersByRole_681AD8378760.md) | Gets the party members by role. |
| Public method Static member | [GetReturnVal(string, int)](ScriptHelpers/Methods/GetReturnVal_6DAA56F46DD6.md) | Gets the return val. |
| Public method Static member | [GetUnfriendlyNpsAtLocation(Func<WoWPoint>, float)](ScriptHelpers/Methods/GetUnfriendlyNpsAtLocation_C73A4BD56356.md) | Trouve les NPCs non-friendly près d'une location |
| Public method Static member | [GetUnfriendlyNpsAtLocation(Func<WoWPoint>, float, Func<WoWUnit, bool>)](ScriptHelpers/Methods/GetUnfriendlyNpsAtLocation_A580556042C4.md) | Gets the unfriendly nps at location. |
| Public method Static member | [IsBossAlive(uint)](ScriptHelpers/Methods/IsBossAlive_EDFD04923ED0.md) | Vérifie si un boss par son ID est encore en vie. Référence HB 4.3.4 ScriptHelpers.cs:464 |
| Public method Static member | [IsBossAlive(string)](ScriptHelpers/Methods/IsBossAlive_8C8ED2B95FAB.md) | Vérifie si un boss nommé est encore en vie. Utilisé par Violet Hold, CoS, Gundrak x10+. |
| Public method Static member | [IsDps(LocalPlayer)](ScriptHelpers/Methods/IsDps_A7A9C1B1DA0D.md) | Determines whether is dps. |
| Public method Static member | [IsFollower(LocalPlayer)](ScriptHelpers/Methods/IsFollower_8E18079223AC.md) | Determines whether is follower. |
| Public method Static member | [IsHealer(LocalPlayer)](ScriptHelpers/Methods/IsHealer_B9B50B00C5C6.md) | Determines whether is healer. |
| Public method Static member | [IsLeader(LocalPlayer)](ScriptHelpers/Methods/IsLeader_6E350CEEFCE2.md) | Determines whether is leader. |
| Public method Static member | [IsMelee(LocalPlayer)](ScriptHelpers/Methods/IsMelee_81FBD50165B0.md) | Determines whether is melee. |
| Public method Static member | [IsRange(LocalPlayer)](ScriptHelpers/Methods/IsRange_6DD88597BC7E.md) | Determines whether is range. |
| Public method Static member | [IsTank(LocalPlayer)](ScriptHelpers/Methods/IsTank_4F91482C7484.md) | Determines whether is tank. |
| Public method Static member | [MarkAsDead(WoWUnit)](ScriptHelpers/Methods/MarkAsDead_42D46665ED46.md) | Marks the unit as dead. |
| Public method Static member | [MoveTankTo(WoWPoint)](ScriptHelpers/Methods/MoveTankTo_0F8C7EA1788B.md) | Fait bouger le tank vers une position |
| Public method Static member | [ShouldKillBoss(string)](ScriptHelpers/Methods/ShouldKillBoss_C20CBC5F89E4.md) | Determines whether should kill boss. |
| Public method Static member | [ShouldKillBoss(uint)](ScriptHelpers/Methods/ShouldKillBoss_48B7ED1DE253.md) | Determines whether should kill boss. |
| Public method Static member | [ToggleMovement](ScriptHelpers/Methods/ToggleMovement_50C56C011452.md) | Converts to ggle movement. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Helpers Namespace](../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
