# LfgManager.AcceptProposal Method

Accepter la proposition de donjon. ⚠️ AcceptProposal() est une fonction Lua RESTRICTED (Protected) en WotLK. Elle nécessite un "hardware event" (clic utilisateur) pour s'exécuter via l'interface Blizzard standard. MAIS CopilotBuddy injecte via EndScene (GreenMagic), ce qui bypass cette restriction car le code s'exécute dans le contexte du thread principal du jeu. Pattern HB: ajout d'un délai aléatoire (1-3s) avant d'accepter pour paraître plus humain et éviter la détection.

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void AcceptProposal()
```

## See Also
[LfgManager Class](../../LfgManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
