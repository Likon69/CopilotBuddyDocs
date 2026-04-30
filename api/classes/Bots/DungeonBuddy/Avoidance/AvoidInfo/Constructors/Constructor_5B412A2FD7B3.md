# AvoidInfo.AvoidInfo Constructor

Initializes a new instance of the AvoidInfo class.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public AvoidInfo(CanRunDecoratorDelegate condition, Func<WoWPoint> locationSelector, Func<float> radiusSelector, Func<WoWPoint> leashPointSelector, float leashRadius, bool isBlocking)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The condition. |
| locationSelector | Func<WoWPoint> | The location selector. |
| radiusSelector | Func<float> | The radius selector. |
| leashPointSelector | Func<WoWPoint> | The leash point selector. |
| leashRadius | float | The leash radius. |
| isBlocking | bool | The is blocking. |

## See Also
[AvoidInfo Class](../../AvoidInfo.md)
[Bots.DungeonBuddy.Avoidance Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
