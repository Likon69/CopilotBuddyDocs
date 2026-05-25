# Bots.DungeonBuddy.Avoidance Namespace

Contains avoidance types used by DungeonBuddy.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [Avoid](../../../classes/Bots/DungeonBuddy/Avoidance/Avoid.md) | Represents an avoid region. |
| Public class | [AvoidCluster](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidCluster.md) | Represents a cluster of avoid regions. |
| Public class | [AvoidInfo](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidInfo.md) | Définit une zone à éviter (ability de boss, feu au sol, etc.) |
| Public class | [AvoidLocation](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidLocation.md) | Represents a location-based avoid region. |
| Public class | [AvoidObject](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidObject.md) | Represents an object-based avoid region. |
| Public class | [AvoidPathNotFoundException](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidPathNotFoundException.md) | Represents an avoid path not found exception. |
| Public class | [AvoidPathResult](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidPathResult.md) | Contains the result of avoid-path calculation. |
| Public class | [AvoidTracelineResult](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidTracelineResult.md) | Contains the result of an avoid traceline test. |
| Public class | [AvoidanceManager](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidanceManager.md) | Provides avoidance management functionality. |
| Public class | [ClusterHit](../../../classes/Bots/DungeonBuddy/Avoidance/ClusterHit.md) | Represents a hit against an avoid cluster. |
| Public class | [Helpers](../../../classes/Bots/DungeonBuddy/Avoidance/Helpers.md) | Provides helper methods for avoid tracing and clustering. |
| Public class | [LineCircleTangentPoints](../../../classes/Bots/DungeonBuddy/Avoidance/LineCircleTangentPoints.md) | Represents tangent points between a line and a circle. |
| Public class | [LineClusterTangentPoints](../../../classes/Bots/DungeonBuddy/Avoidance/LineClusterTangentPoints.md) | Represents tangent points between a line and a cluster. |
| Public class | [WorldObstacleManager](../../../classes/Bots/DungeonBuddy/Avoidance/WorldObstacleManager.md) | Provides world obstacle management functionality. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [AvoidSide](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidSide.md) | Represents values for Avoid Side. |
| Public enumeration | [AvoidancePriority](../../../classes/Bots/DungeonBuddy/Avoidance/AvoidancePriority.md) | HB 6.2.3 AvoidancePriority — weights the urgency of an avoid zone. Used by GetBestLocationOutsideCluster to bias the escape route scoring: high-priority avoids (e.g. instant-kill fire) dominate the score so the bot exits through them first, even if the path is longer. Values match HB 6.2.3 exactly: Low=1, Medium=10, High=100. |
| Public enumeration | [PathResult](../../../classes/Bots/DungeonBuddy/Avoidance/PathResult.md) | Represents values for Path Result. |

## See Also
[Namespace Index](../../../index.md)
