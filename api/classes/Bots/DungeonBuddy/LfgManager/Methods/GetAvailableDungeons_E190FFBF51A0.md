# LfgManager.GetAvailableDungeons Method

Liste des donjons disponibles pour le niveau actuel. NOTE: GetDungeonInfo(i) existe en WotLK mais n'est PAS GetLFGDungeonInfo(). GetNumDungeons() et GetDungeonInfo() sont des API de LFDFrame.

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static List<(uint Id, string Name, bool IsHeroic)> GetAvailableDungeons()
```

## Return Value

Type: List<(uint Id, string Name, bool IsHeroic)>
The result of the operation.

## See Also
[LfgManager Class](../../LfgManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
