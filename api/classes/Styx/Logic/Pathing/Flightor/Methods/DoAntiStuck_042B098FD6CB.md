# Flightor.DoAntiStuck Method

Stateful 3-step anti-stuck maneuver (WoD port). Steps: JumpAscend → StrafeLeft → StrafeRight → Backwards → reset. Each call advances one step; state resets when the bot moves > 10m.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void DoAntiStuck()
```

## See Also
[Flightor Class](../../Flightor.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
