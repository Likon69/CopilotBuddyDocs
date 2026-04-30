# ICombatRoutine Interface

Defines the contract for I Combat Routine.

## Namespace
[Styx.Combat.CombatRoutine](../../../../namespaces/Styx/Combat/CombatRoutine.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public interface ICombatRoutine : IBehaviors, IDisposable
```

The ICombatRoutine type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ButtonText](ICombatRoutine/Properties/ButtonText_DDD822D98FE2.md) | Gets the button text. |
| Public property | [Class](ICombatRoutine/Properties/Class_BB842F25422C.md) | Gets the class. |
| Public property | [Name](ICombatRoutine/Properties/Name_6DA2FE51D8E9.md) | Gets the name. |
| Public property | [NeedCombatBuffs](ICombatRoutine/Properties/NeedCombatBuffs_6F9CAA8539E1.md) | Gets a value indicating whether need combat buffs. |
| Public property | [NeedHeal](ICombatRoutine/Properties/NeedHeal_4DD626E27C35.md) | Gets a value indicating whether need heal. |
| Public property | [NeedPreCombatBuffs](ICombatRoutine/Properties/NeedPreCombatBuffs_C28979209158.md) | Gets a value indicating whether need pre combat buffs. |
| Public property | [NeedPullBuffs](ICombatRoutine/Properties/NeedPullBuffs_0C618E572AF2.md) | Gets a value indicating whether need pull buffs. |
| Public property | [NeedRest](ICombatRoutine/Properties/NeedRest_C401707BEE64.md) | Gets a value indicating whether need rest. |
| Public property | [PullDistance](ICombatRoutine/Properties/PullDistance_C055B5DC3A43.md) | Gets the pull distance. |
| Public property | [WantButton](ICombatRoutine/Properties/WantButton_F43271638B8C.md) | Gets a value indicating whether want button. |
| Public property | [CombatBehavior](IBehaviors/Properties/CombatBehavior_DEBBE85FEA4C.md) | Gets the combat behavior. (Inherited from IBehaviors.) |
| Public property | [CombatBuffBehavior](IBehaviors/Properties/CombatBuffBehavior_A2C144A925D6.md) | Gets the combat buff behavior. (Inherited from IBehaviors.) |
| Public property | [HealBehavior](IBehaviors/Properties/HealBehavior_E4DCB87B078D.md) | Gets the heal behavior. (Inherited from IBehaviors.) |
| Public property | [MoveToTargetBehavior](IBehaviors/Properties/MoveToTargetBehavior_DB4E6AAC164D.md) | Gets the move to target behavior. (Inherited from IBehaviors.) |
| Public property | [PreCombatBuffBehavior](IBehaviors/Properties/PreCombatBuffBehavior_AB8C7E4F96C4.md) | Gets the pre combat buff behavior. (Inherited from IBehaviors.) |
| Public property | [PullBehavior](IBehaviors/Properties/PullBehavior_EF76A76700C5.md) | Gets the pull behavior. (Inherited from IBehaviors.) |
| Public property | [PullBuffBehavior](IBehaviors/Properties/PullBuffBehavior_386D3EE8A78F.md) | Gets the pull buff behavior. (Inherited from IBehaviors.) |
| Public property | [RestBehavior](IBehaviors/Properties/RestBehavior_1F1126B74DBD.md) | Gets the rest behavior. (Inherited from IBehaviors.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Combat](ICombatRoutine/Methods/Combat_EA681CA7ED8C.md) | Creates the combat behavior. |
| Public method | [CombatBuff](ICombatRoutine/Methods/CombatBuff_26A6346B0636.md) | Creates the combat buff behavior. |
| Public method | [Heal](ICombatRoutine/Methods/Heal_74A28C2E8E45.md) | Creates the heal behavior. |
| Public method | [Initialize](ICombatRoutine/Methods/Initialize_C593963256D1.md) | Initializes the component. |
| Public method | [OnButtonPress](ICombatRoutine/Methods/OnButtonPress_57B5E72D6C87.md) | Handles the on button press operation. |
| Public method | [PreCombatBuff](ICombatRoutine/Methods/PreCombatBuff_FB26D037823A.md) | Creates the pre-combat buff behavior. |
| Public method | [Pull](ICombatRoutine/Methods/Pull_C9F13E9D541B.md) | Creates the pull behavior. |
| Public method | [PullBuff](ICombatRoutine/Methods/PullBuff_571442DC95C9.md) | Creates the pull buff behavior. |
| Public method | [Pulse](ICombatRoutine/Methods/Pulse_86B0203D288A.md) | Executes one bot pulse. |
| Public method | [Rest](ICombatRoutine/Methods/Rest_1EC99A5FF63D.md) | Creates the rest behavior. |
| Public method | [ShutDown](ICombatRoutine/Methods/ShutDown_CE36B6FB0B0F.md) | Called when the combat routine is shutting down. Used for cleanup (timers, event handlers, etc.). |
| Public method | Dispose | Releases the resources used by the instance. (Inherited from IDisposable.) |

## See Also
[Styx.Combat.CombatRoutine Namespace](../../../../namespaces/Styx/Combat/CombatRoutine.md)
