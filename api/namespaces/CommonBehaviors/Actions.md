# CommonBehaviors.Actions Namespace

Contains reusable behavior tree action types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [ActionAlwaysFail](../../classes/CommonBehaviors/Actions/ActionAlwaysFail.md) | Represents an action that always fails. |
| Public class | [ActionAlwaysSucceed](../../classes/CommonBehaviors/Actions/ActionAlwaysSucceed.md) | Represents an action that always succeeds. |
| Public class | [ActionClearPoi](../../classes/CommonBehaviors/Actions/ActionClearPoi.md) | Represents an action that clears the current point of interest. |
| Public class | [ActionDebugString](../../classes/CommonBehaviors/Actions/ActionDebugString.md) | Represents an action that writes a debug string. |
| Public class | [ActionIdle](../../classes/CommonBehaviors/Actions/ActionIdle.md) | Represents an idle action. |
| Public class | [ActionInteract](../../classes/CommonBehaviors/Actions/ActionInteract.md) | Represents an interact action. |
| Public class | [ActionMoveStop](../../classes/CommonBehaviors/Actions/ActionMoveStop.md) | Represents a move stop action. |
| Public class | [ActionMoveToPoi](../../classes/CommonBehaviors/Actions/ActionMoveToPoi.md) | HB MoP/WoD style ActionMoveToPoi with anti-spam logging. Tracks last target GUID and location to avoid spamming logs. |
| Public class | [ActionMoveToPoint](../../classes/CommonBehaviors/Actions/ActionMoveToPoint.md) | Represents a move to point action. |
| Public class | [ActionRunCoroutine](../../classes/CommonBehaviors/Actions/ActionRunCoroutine.md) | Port of HB 6.2.3 CommonBehaviors.Actions.ActionRunCoroutine. Bridges async Task-based coroutines with TreeSharp's synchronous behavior tree. Each Tick() calls Coroutine.Resume() which advances the async method by one step. |
| Public class | [ActionSetActivity](../../classes/CommonBehaviors/Actions/ActionSetActivity.md) | Represents a set activity action. |
| Public class | [ActionSetPoi](../../classes/CommonBehaviors/Actions/ActionSetPoi.md) | Represents a set point of interest action. |
| Public class | [ActionSleep](../../classes/CommonBehaviors/Actions/ActionSleep.md) | Represents a sleep action. |
| Public class | [NavigationAction](../../classes/CommonBehaviors/Actions/NavigationAction.md) | Represents a navigation action. |
| Public class | [SequenceOpenGossip](../../classes/CommonBehaviors/Actions/SequenceOpenGossip.md) | Represents an open gossip sequence. |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [ActionSetActivity.GetStatusTextDelegate](../../classes/CommonBehaviors/Actions/ActionSetActivity/GetStatusTextDelegate.md) | Represents a delegate for get status text. |
| Public delegate | [DebugStringDelegate](../../classes/CommonBehaviors/Actions/DebugStringDelegate.md) | Represents a delegate for debug string. |
| Public delegate | [GetPointDelegate](../../classes/CommonBehaviors/Actions/GetPointDelegate.md) | Represents a delegate for get point. |
| Public delegate | [RetrieveBotPoiDelegate](../../classes/CommonBehaviors/Actions/RetrieveBotPoiDelegate.md) | Represents a delegate for retrieve bot point of interest. |

## See Also
[Namespace Index](../../index.md)
