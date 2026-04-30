# LfgManager.CurrentState Property

État actuel du LFG. Utilise GetLFGMode() — API canonique confirmée WotLK 3.3. NOTE: En WotLK 3.3, GetLFGMode() ne prend AUCUN argument (le paramètre category a été ajouté en MoP 5.x). Retourne: "queued", "proposal", "lfgparty", "abandonedInDungeon", "suspended", "rolecheck", ou nil C'est la même méthode utilisée par HB 4.3.4 DungeonBuddy.

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static LfgState CurrentState { get; }
```

## Property Value

Type: [LfgState](../../Enums/LfgState.md)
The current state.

## See Also
[LfgManager Class](../../LfgManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
