# Styx.Logic.Profiles.Quest Namespace

Contains quest profile helper and compilation types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [AbandonQuestNode](../../../../classes/Styx/Logic/Profiles/Quest/AbandonQuestNode.md) | Represents an abandon quest node. |
| Public class | [CheckpointNode](../../../../classes/Styx/Logic/Profiles/Quest/CheckpointNode.md) | Represents a checkpoint node. |
| Public class | [ClearGrindAreaNode](../../../../classes/Styx/Logic/Profiles/Quest/ClearGrindAreaNode.md) | Represents a clear grind area node. |
| Public class | [ClearMailboxNode](../../../../classes/Styx/Logic/Profiles/Quest/ClearMailboxNode.md) | Represents a clear mailbox node. |
| Public class | [ClearVendorNode](../../../../classes/Styx/Logic/Profiles/Quest/ClearVendorNode.md) | Represents a clear vendor node. |
| Public class | [CodeNode](../../../../classes/Styx/Logic/Profiles/Quest/CodeNode.md) | Represents a code node. |
| Public class | [CollectFrom](../../../../classes/Styx/Logic/Profiles/Quest/CollectFrom.md) | Represents a source for collecting items (mob, gameobject, or vendor). |
| Public class | [CollectFromCollection](../../../../classes/Styx/Logic/Profiles/Quest/CollectFromCollection.md) | Collection of CollectFrom sources. |
| Public class | [CollectItemObjectiveInfo](../../../../classes/Styx/Logic/Profiles/Quest/CollectItemObjectiveInfo.md) | Objective info for collecting items. |
| Public class | [CompileBatch](../../../../classes/Styx/Logic/Profiles/Quest/CompileBatch.md) | Batches C# expression strings from quest behaviors and compiles them together into a single assembly whose class inherits ProfileHelperFunctionsBase. Ported from HB 6.2.3 Styx.CommonBot.Profiles.Quest.Order.CompileBatch, using Roslyn instead of CodeDom. |
| Public class | [CompileError](../../../../classes/Styx/Logic/Profiles/Quest/CompileError.md) | Represents a compilation error produced by CompileBatch. Ported from HB 6.2.3 Styx.CommonBot.Profiles.Quest.Order.CompileError. |
| Public class | [ConditionGlobals](../../../../classes/Styx/Logic/Profiles/Quest/ConditionGlobals.md) | Globals object for Roslyn script evaluation. Provides Me property (like ProfileHelperFunctionsBase in HB) |
| Public class | [ConditionHelper](../../../../classes/Styx/Logic/Profiles/Quest/ConditionHelper.md) | Compiles and evaluates C# condition expressions at runtime. Implements same pattern as HB 6.2.3 ConditionHelper with: - Fast-path parser for common expressions (Class, Race, Level, HasQuest, IsQuestCompleted) - Roslyn fallback for complex expressions - Expression caching to prevent memory issues |
| Public class | [DelayCompiledExpression](../../../../classes/Styx/Logic/Profiles/Quest/DelayCompiledExpression.md) | Holds a C# expression string whose delegate is compiled lazily by CompileBatch. The CallableExpression property is always callable but throws if Compile() has not been called. Ported from HB 6.2.3 Styx.CommonBot.Profiles.Quest.Order.DelayCompiledExpression. |
| Public class | [DelayCompiledExpression<T>](../../../../classes/Styx/Logic/Profiles/Quest/DelayCompiledExpression_1.md) | Typed variant of DelayCompiledExpression. Ported from HB 6.2.3 Styx.CommonBot.Profiles.Quest.Order.DelayCompiledExpression<T>. |
| Public class | [DisableRepairNode](../../../../classes/Styx/Logic/Profiles/Quest/DisableRepairNode.md) | Represents a disable repair node. |
| Public class | [Else](../../../../classes/Styx/Logic/Profiles/Quest/Else.md) | Represents an else. |
| Public class | [ElseIf](../../../../classes/Styx/Logic/Profiles/Quest/ElseIf.md) | Represents an else if. |
| Public class | [EnableRepairNode](../../../../classes/Styx/Logic/Profiles/Quest/EnableRepairNode.md) | Represents an enable repair node. |
| Public class | [GrindToNode](../../../../classes/Styx/Logic/Profiles/Quest/GrindToNode.md) | Node for grinding to a specific level. |
| Public class | [IfNode](../../../../classes/Styx/Logic/Profiles/Quest/IfNode.md) | Represents an if node. |
| Public class | [KillMobObjectiveInfo](../../../../classes/Styx/Logic/Profiles/Quest/KillMobObjectiveInfo.md) | Objective info for killing mobs. |
| Public class | [MoveToNode](../../../../classes/Styx/Logic/Profiles/Quest/MoveToNode.md) | Represents a move to node. |
| Public class | [ObjectiveInfo](../../../../classes/Styx/Logic/Profiles/Quest/ObjectiveInfo.md) | Base class for quest objective information. |
| Public class | [ObjectiveNode](../../../../classes/Styx/Logic/Profiles/Quest/ObjectiveNode.md) | Represents an objective node. |
| Public class | [OrderNode](../../../../classes/Styx/Logic/Profiles/Quest/OrderNode.md) | Represents an order node. |
| Public class | [OrderNodeCollection](../../../../classes/Styx/Logic/Profiles/Quest/OrderNodeCollection.md) | Represents a collection of order node. |
| Public class | [PickUpNode](../../../../classes/Styx/Logic/Profiles/Quest/PickUpNode.md) | Represents a pick up node. |
| Public class | [ProfileBatchManager](../../../../classes/Styx/Logic/Profiles/Quest/ProfileBatchManager.md) | Manages the per-profile CompileBatch for quest behaviors that use [CompileString] / [CompileExpression] (e.g. RunCode). Flow (mirrors HB WoD Class1208 semantics): 1. QuestBot.Start() → ProfileBatchManager.Reset() 2. ForcedCodeBehavior ctor → ProfileBatchManager.Register(qbInstance) 3. ForcedCodeBehavior.OnStart() → ProfileBatchManager.EnsureCompiled() Because CB executes nodes sequentially, Definition QBs are registered before any Statement QB tries to compile, so cross-node variable sharing works. |
| Public class | [ProfileHelperFunctions](../../../../classes/Styx/Logic/Profiles/Quest/ProfileHelperFunctions.md) | Profile helper functions for quest conditions - same as HB |
| Public class | [ProfileHelperFunctionsBase](../../../../classes/Styx/Logic/Profiles/Quest/ProfileHelperFunctionsBase.md) | Represents a profile helper functions base. |
| Public class | [QuestBehaviorHelper](../../../../classes/Styx/Logic/Profiles/Quest/QuestBehaviorHelper.md) | Compiles Quest Behaviors from C# source files at runtime using Roslyn. Quest Behaviors are placed in the "Quest Behaviors" folder next to the executable. Supports both single .cs files and folders containing multiple .cs files. Usage in profile XML: |
| Public class | [QuestInfo](../../../../classes/Styx/Logic/Profiles/Quest/QuestInfo.md) | Information about a quest. |
| Public class | [SetGrindAreaNode](../../../../classes/Styx/Logic/Profiles/Quest/SetGrindAreaNode.md) | Represents a set grind area node. |
| Public class | [SetMailboxNode](../../../../classes/Styx/Logic/Profiles/Quest/SetMailboxNode.md) | Represents a set mailbox node. |
| Public class | [SetVendorNode](../../../../classes/Styx/Logic/Profiles/Quest/SetVendorNode.md) | Represents a set vendor node. |
| Public class | [TurnInNode](../../../../classes/Styx/Logic/Profiles/Quest/TurnInNode.md) | Represents a turn in node. |
| Public class | [TurnInObjectiveInfo](../../../../classes/Styx/Logic/Profiles/Quest/TurnInObjectiveInfo.md) | Objective info for turning in a quest. |
| Public class | [UseItemNode](../../../../classes/Styx/Logic/Profiles/Quest/UseItemNode.md) | Represents a use item node. |
| Public class | [UseObjectObjectiveInfo](../../../../classes/Styx/Logic/Profiles/Quest/UseObjectObjectiveInfo.md) | Objective info for using objects. |
| Public class | [WhileNode](../../../../classes/Styx/Logic/Profiles/Quest/WhileNode.md) | Represents a while node. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [INodeContainer](../../../../classes/Styx/Logic/Profiles/Quest/INodeContainer.md) | Defines the contract for I Node Container. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [CollectFromType](../../../../classes/Styx/Logic/Profiles/Quest/CollectFromType.md) | Type of source for collecting items. |
| Public enumeration | [ObjectiveType](../../../../classes/Styx/Logic/Profiles/Quest/ObjectiveType.md) | Types of quest objectives. |
| Public enumeration | [OrderNodeType](../../../../classes/Styx/Logic/Profiles/Quest/OrderNodeType.md) | Represents values for Order Node Type. |
| Public enumeration | [QuestObjectType](../../../../classes/Styx/Logic/Profiles/Quest/QuestObjectType.md) | Represents values for Quest Object Type. |
| Public enumeration | [UseItemNode.UseItemTargetType](../../../../classes/Styx/Logic/Profiles/Quest/UseItemNode/UseItemTargetType.md) | Represents values for Use Item Target Type. |

## See Also
[Namespace Index](../../../../index.md)
