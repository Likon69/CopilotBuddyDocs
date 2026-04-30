# TreeSharp Namespace

Contains behavior tree primitives and composite types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [Action](../classes/TreeSharp/Action.md) | Represents an action node. |
| Public class | [Composite](../classes/TreeSharp/Composite.md) | Represents a composite. |
| Public class | [CompositeExtensions](../classes/TreeSharp/CompositeExtensions.md) | Represents a composite extensions. |
| Public class | [Decorator](../classes/TreeSharp/Decorator.md) | Represents a decorator node. |
| Public class | [DecoratorContinue](../classes/TreeSharp/DecoratorContinue.md) | DecoratorContinue - Exact HB WoD/MoP implementation |
| Public class | [GroupComposite](../classes/TreeSharp/GroupComposite.md) | Represents a composite node that manages child composites. |
| Public class | [PrioritySelector](../classes/TreeSharp/PrioritySelector.md) | Will execute each branch of logic in order, until one succeeds. This composite will fail only if all branches fail as well. |
| Public class | [ProbabilitySelection](../classes/TreeSharp/ProbabilitySelection.md) | Represents a probability-weighted selection entry. |
| Public class | [ProbabilitySelector](../classes/TreeSharp/ProbabilitySelector.md) | Will execute random branches of logic, until one succeeds. This composite will fail only if all branches fail as well. |
| Public class | [Selector](../classes/TreeSharp/Selector.md) | The base selector class. This will attempt to execute all branches of logic, until one succeeds. This composite will fail only if all branches fail as well. |
| Public class | [Sequence](../classes/TreeSharp/Sequence.md) | The base sequence class. This will execute each branch of logic, in order. If all branches succeed, this composite will return a successful run status. If any branch fails, this composite will return a failed run status. |
| Public class | [Switch<T>](../classes/TreeSharp/Switch_1.md) | This composite will perform a 'switch' statement to execute a specific branch of logic. This is useful for selecting specific branches, for different types of agents. (e.g. rogue, mage, and warrior branches) |
| Public class | [SwitchArgument<T>](../classes/TreeSharp/SwitchArgument_1.md) | Represents a switch argument. |
| Public class | [Wait](../classes/TreeSharp/Wait.md) | Represents a wait. |
| Public class | [WaitContinue](../classes/TreeSharp/WaitContinue.md) | Represents a wait continuation node. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [RunStatus](../classes/TreeSharp/RunStatus.md) | Values that can be returned from composites and the like. |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [ActionDelegate](../classes/TreeSharp/ActionDelegate.md) | Represents a delegate for action. |
| Public delegate | [ActionSucceedDelegate](../classes/TreeSharp/ActionSucceedDelegate.md) | Represents a delegate for action succeed. |
| Public delegate | [CanRunDecoratorDelegate](../classes/TreeSharp/CanRunDecoratorDelegate.md) | Represents a delegate for can run decorator. |
| Public delegate | [ContextChangeHandler](../classes/TreeSharp/ContextChangeHandler.md) | Represents a delegate for Context Change Handler. |
| Public delegate | [RetrieveSwitchParameterDelegate<T>](../classes/TreeSharp/RetrieveSwitchParameterDelegate_1.md) | Represents a delegate for retrieve switch parameter. |
| Public delegate | [WaitGetTimeoutDelegate](../classes/TreeSharp/WaitGetTimeoutDelegate.md) | Represents a delegate for wait get timeout. |

## See Also
[Namespace Index](../index.md)
