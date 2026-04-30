# CombatRoutine Class

Represents a combat routine.

## Inheritance Hierarchy
System.Object
  System.MarshalByRefObject
    Styx.Combat.CombatRoutine.CombatRoutine

## Namespace
[Styx.Combat.CombatRoutine](../../../../namespaces/Styx/Combat/CombatRoutine.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class CombatRoutine : MarshalByRefObject, IBehaviors, ICombatRoutine, IDisposable
```

The CombatRoutine type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [CombatRoutine](CombatRoutine/Constructors/Constructor_3956757628EB.md) | Initializes a new instance of the CombatRoutine class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ButtonText](CombatRoutine/Properties/ButtonText_46A064AA64EE.md) | Gets the button text. |
| Public property | [Class](CombatRoutine/Properties/Class_BE7043ED2D69.md) | Gets the class. |
| Public property | [CombatBehavior](CombatRoutine/Properties/CombatBehavior_8694B181D8A7.md) | Gets the combat behavior. |
| Public property | [CombatBuffBehavior](CombatRoutine/Properties/CombatBuffBehavior_105788DDD761.md) | Gets the combat buff behavior. |
| Public property | [HealBehavior](CombatRoutine/Properties/HealBehavior_9E5ACB3DF3F6.md) | Gets the heal behavior. |
| Public property | [MoveToTargetBehavior](CombatRoutine/Properties/MoveToTargetBehavior_FB031B6B39DB.md) | Gets the move to target behavior. |
| Public property | [Name](CombatRoutine/Properties/Name_B558AA3C0B9A.md) | Gets the name. |
| Public property | [NeedCombatBuffs](CombatRoutine/Properties/NeedCombatBuffs_234AB3357BF4.md) | Gets a value indicating whether need combat buffs. |
| Public property | [NeedHeal](CombatRoutine/Properties/NeedHeal_30155D227B1F.md) | Gets a value indicating whether need heal. |
| Public property | [NeedPreCombatBuffs](CombatRoutine/Properties/NeedPreCombatBuffs_409E3B01F0F2.md) | Gets a value indicating whether need pre combat buffs. |
| Public property | [NeedPullBuffs](CombatRoutine/Properties/NeedPullBuffs_5A986566E77E.md) | Gets a value indicating whether need pull buffs. |
| Public property | [NeedRest](CombatRoutine/Properties/NeedRest_7CA2DC5D5379.md) | Gets a value indicating whether need rest. |
| Public property | [PreCombatBuffBehavior](CombatRoutine/Properties/PreCombatBuffBehavior_1B41415C974E.md) | Gets the pre combat buff behavior. |
| Public property | [PullBehavior](CombatRoutine/Properties/PullBehavior_C0B1C13AB14E.md) | Gets the pull behavior. |
| Public property | [PullBuffBehavior](CombatRoutine/Properties/PullBuffBehavior_BF61D0D0E6E2.md) | Gets the pull buff behavior. |
| Public property | [PullDistance](CombatRoutine/Properties/PullDistance_929BAAE969AE.md) | Gets the pull distance. |
| Public property | [RestBehavior](CombatRoutine/Properties/RestBehavior_1077EAED41AD.md) | BUG-05 fix: Returns a Decorator wrapping the legacy Rest() method. HB 4.3.4 pattern: Decorator(NeedRest, Action(Rest)) |
| Public property | [WantButton](CombatRoutine/Properties/WantButton_A45E525B2896.md) | Gets a value indicating whether want button. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Combat](CombatRoutine/Methods/Combat_2A2A7F97660F.md) | Creates the combat behavior. |
| Public method | [CombatBuff](CombatRoutine/Methods/CombatBuff_E6FAF678880D.md) | Creates the combat buff behavior. |
| Public method | [Dispose](CombatRoutine/Methods/Dispose_EF5817185AB0.md) | Releases the resources used by the instance. |
| Public method | [Heal](CombatRoutine/Methods/Heal_6E1BC9384870.md) | Creates the heal behavior. |
| Public method | [Initialize](CombatRoutine/Methods/Initialize_FECC044C8831.md) | Initializes the component. |
| Public method | [OnButtonPress](CombatRoutine/Methods/OnButtonPress_E8763867B5B7.md) | Handles the on button press operation. |
| Public method | [PreCombatBuff](CombatRoutine/Methods/PreCombatBuff_1FEAE383E29F.md) | Creates the pre-combat buff behavior. |
| Public method | [Pull](CombatRoutine/Methods/Pull_ED43CA507F65.md) | Creates the pull behavior. |
| Public method | [PullBuff](CombatRoutine/Methods/PullBuff_00A22CC36EA9.md) | Creates the pull buff behavior. |
| Public method | [Pulse](CombatRoutine/Methods/Pulse_594AA3690B2E.md) | Executes one bot pulse. |
| Public method | [Rest](CombatRoutine/Methods/Rest_E8F4A03443D1.md) | Creates the rest behavior. |
| Public method | [ShutDown](CombatRoutine/Methods/ShutDown_029A98C6BEE2.md) | Shuts down the routine. |
| Public method | [ToString](CombatRoutine/Methods/ToString_09F9BFBC4C5E.md) | Display string for routine selection UI. HB 4.3.4 pattern. (Overrides object.ToString().) |
| Public method | GetLifetimeService | Gets the lifetime service. (Inherited from MarshalByRefObject.) |
| Public method | InitializeLifetimeService | Initializes the lifetime service. (Inherited from MarshalByRefObject.) |
| Protected method | MemberwiseClone(bool) | Creates a shallow copy of the current Object. (Inherited from MarshalByRefObject.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Combat.CombatRoutine Namespace](../../../../namespaces/Styx/Combat/CombatRoutine.md)
