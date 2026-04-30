# Styx.Logic.BehaviorTree Namespace

Contains behavior tree support types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [StatusTextChangedEventArgs](../../../classes/Styx/Logic/BehaviorTree/StatusTextChangedEventArgs.md) | Event args for TreeRoot.OnStatusTextChanged — same as HB 4.3.4 |
| Public class | [TreeRoot](../../../classes/Styx/Logic/BehaviorTree/TreeRoot.md) | Represents a tree root. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [LogicType](../../../classes/Styx/Logic/BehaviorTree/LogicType.md) | Represents values for Logic Type. |
| Public enumeration | [TreeRootState](../../../classes/Styx/Logic/BehaviorTree/TreeRootState.md) | State machine for TreeRoot lifecycle — matches HB 6.2.3. Prevents race conditions between UI thread (Stop) and worker thread (Tick). |

## See Also
[Namespace Index](../../../index.md)
