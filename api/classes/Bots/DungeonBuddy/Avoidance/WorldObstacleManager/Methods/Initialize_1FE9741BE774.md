# WorldObstacleManager.Initialize Method

Registers common world obstacle types and wires Navigator callbacks. Safe to call multiple times — re-registers cleanly on each bot start. HB 6.2.3: AvoidanceNavigationProvider is set as NavigationProvider in DungeonBuddy.Start(). Here we use Navigator delegate injection (no NavigationProvider subclass needed).

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void Initialize()
```

## See Also
[WorldObstacleManager Class](../../WorldObstacleManager.md)
[Bots.DungeonBuddy.Avoidance Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
