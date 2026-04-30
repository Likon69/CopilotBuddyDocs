# Quest.GetData Method

Gets descriptor data for this quest from the player's quest log. Reads the 25 quest log slots in the player descriptor table. Layout per slot (5 descriptor indices each, starting at 0x9E): +0: Quest ID (uint) +1: State flags (uint → WoWDescriptorQuestFlags) +2: Objective counts low (2 packed ushorts: objectives 0,1) +3: Objective counts high (2 packed ushorts: objectives 2,3) +4: Timer (uint, seconds before failed)

## Namespace
[Styx.Logic.Questing](../../../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool GetData(out QuestDescriptorData data)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | [QuestDescriptorData](../../QuestDescriptorData.md) | The data. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[Quest Class](../../Quest.md)
[Styx.Logic.Questing Namespace](../../../../../../namespaces/Styx/Logic/Questing.md)
