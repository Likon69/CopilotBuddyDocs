# LfgManager Class

Gère l'interface avec le Dungeon Finder (LFG). Compatible WotLK 3.3 - Dungeon Finder ajouté en patch 3.3.

## Namespace
[Bots.DungeonBuddy](../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class LfgManager
```

The LfgManager type exposes the following members.

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [ExitDelayTimer](LfgManager/Fields/ExitDelayTimer_971A879C8CC7.md) | Exit delay timer (HB waitTimer_7) — set on DungeonCompleted to trigger leave |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [BootProposalActive](LfgManager/Properties/BootProposalActive_3539A553431D.md) | Flag: LFG_COMPLETION_REWARD received (HB bool_7) |
| Public property Static member | [CurrentDifficulty](LfgManager/Properties/CurrentDifficulty_C16092B99B15.md) | Obtient la difficulté du donjon actuel (1=Normal, 2=Heroic) |
| Public property Static member | [CurrentLfgDungeonId](LfgManager/Properties/CurrentLfgDungeonId_D5D090A6E037.md) | ID du donjon LFG actuel (depuis GetPartyLFGID()). Retourne 0 si pas dans un groupe LFG. HB 4.3.4: DungeonManager utilise cette valeur pour choisir le script de donjon. |
| Public property Static member | [CurrentMapId](LfgManager/Properties/CurrentMapId_81F7A9A4B78B.md) | Obtient le MapID du donjon actuel |
| Public property Static member | [CurrentState](LfgManager/Properties/CurrentState_DC4CCEB4B4E0.md) | État actuel du LFG. Utilise GetLFGMode() — API canonique confirmée WotLK 3.3. NOTE: En WotLK 3.3, GetLFGMode() ne prend AUCUN argument (le paramètre category a été ajouté en MoP 5.x). Retourne: "queued", "proposal", "lfgparty", "abandonedInDungeon", "suspended", "rolecheck", ou nil C'est la même méthode utilisée par HB 4.3.4 DungeonBuddy. |
| Public property Static member | [DungeonCompletedReason](LfgManager/Properties/DungeonCompletedReason_DA8A1F774261.md) | Completion reason enum (HB completeReason_0) |
| Public property Static member | [EstimatedWaitTime](LfgManager/Properties/EstimatedWaitTime_99AF05999EDC.md) | Temps d'attente estimé (en secondes) |
| Public property Static member | [PartyInvitePending](LfgManager/Properties/PartyInvitePending_9776D06C617C.md) | Flag: party invite request (HB bool_9) |
| Public property Static member | [ProposalFailed](LfgManager/Properties/ProposalFailed_62B59C3AFBD0.md) | Flag: proposal failed (HB bool_4) |
| Public property Static member | [ProposalPending](LfgManager/Properties/ProposalPending_55134B2D4806.md) | Flag: un proposal est en attente (HB bool_6) |
| Public property Static member | [ProposalSucceeded](LfgManager/Properties/ProposalSucceeded_D80B3EFD7EF4.md) | Flag: proposal succeeded (HB bool_5) |
| Public property Static member | [ResurrectRequestPending](LfgManager/Properties/ResurrectRequestPending_462EBBAB761F.md) | Flag: resurrect request (HB bool_3) |
| Public property Static member | [RoleCheckPending](LfgManager/Properties/RoleCheckPending_E00401184BCD.md) | Flag: role check popup shown (HB bool_8) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AcceptProposal](LfgManager/Methods/AcceptProposal_7E057E1B214C.md) | Accepter la proposition de donjon. Parité HB: appel direct Lua AcceptProposal(). |
| Public method Static member | [AttachLfgEvents](LfgManager/Methods/AttachLfgEvents_001E2574234C.md) | Attache les événements LFG via Lua.Events.AttachEvent Appelé dans DungeonBuddy.Start() |
| Public method Static member | [DeclineProposal](LfgManager/Methods/DeclineProposal_A3BCDBA06961.md) | Refuser la proposition |
| Public method Static member | [DetachLfgEvents](LfgManager/Methods/DetachLfgEvents_5FA0C0A085D8.md) | Détache les événements LFG. Appelé dans DungeonBuddy.Stop() |
| Public method Static member | [GetAvailableDungeons](LfgManager/Methods/GetAvailableDungeons_E190FFBF51A0.md) | Liste des donjons disponibles pour le niveau actuel. NOTE: GetDungeonInfo(i) existe en WotLK mais n'est PAS GetLFGDungeonInfo(). GetNumDungeons() et GetDungeonInfo() sont des API de LFDFrame. |
| Public method Static member | [GetAvailableRoles](LfgManager/Methods/GetAvailableRoles_B96904365B63.md) | Obtient les rôles disponibles pour la classe actuelle |
| Public method Static member | [LeaveQueue](LfgManager/Methods/LeaveQueue_D6D1F5702853.md) | Quitter la queue |
| Public method Static member | [QueueForRandomDungeon](LfgManager/Methods/QueueForRandomDungeon_E3F8B968CEFC.md) | Queue pour un donjon aléatoire |
| Public method Static member | [QueueForRandomHeroic](LfgManager/Methods/QueueForRandomHeroic_53EC40EFF01A.md) | Queue pour un héroïque aléatoire |
| Public method Static member | [QueueForSpecificDungeon(uint)](LfgManager/Methods/QueueForSpecificDungeon_6F20171B1DD1.md) | Queue pour un donjon spécifique |
| Public method Static member | [ResetProposalFlags](LfgManager/Methods/ResetProposalFlags_31EF28A4040F.md) | Resets the proposal flags. |
| Public method Static member | [SetDungeonCompleted(CompleteReason, int)](LfgManager/Methods/SetDungeonCompleted_E69CA171DD58.md) | HB smethod_23: set DungeonCompleted + reset ExitDelayTimer |
| Public method Static member | [SetRole(PartyRole)](LfgManager/Methods/SetRole_4CB2182709A7.md) | Définit le rôle pour le LFG |
| Public method Static member | [TeleportIn](LfgManager/Methods/TeleportIn_36D3603B79FC.md) | Téléporte dans le donjon |
| Public method Static member | [TeleportOut](LfgManager/Methods/TeleportOut_709D30B5AB46.md) | Téléporte hors du donjon |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy Namespace](../../../namespaces/Bots/DungeonBuddy.md)
