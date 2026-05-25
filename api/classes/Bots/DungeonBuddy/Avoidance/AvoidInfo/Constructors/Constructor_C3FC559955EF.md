# AvoidInfo.AvoidInfo Constructor

Initializes a new instance of the AvoidInfo class.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public AvoidInfo(CanRunDecoratorDelegate condition, Predicate<WoWObject> objectSelector, Func<float> radiusSelector, Func<WoWPoint> leashPointSelector, float leashRadius, bool isBlocking, AvoidancePriority priority)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The condition. |
| objectSelector | Predicate<WoWObject> | The object selector. |
| radiusSelector | Func<float> | The radius selector. |
| leashPointSelector | Func<WoWPoint> | The leash point selector. |
| leashRadius | float | The leash radius. |
| isBlocking | bool | The is blocking. |
| priority | [AvoidancePriority](../../AvoidancePriority.md) | The priority. |

## See Also
[AvoidInfo Class](../../AvoidInfo.md)
[Bots.DungeonBuddy.Avoidance Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
