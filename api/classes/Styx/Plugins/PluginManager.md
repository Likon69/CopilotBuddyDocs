# PluginManager Class

Manages plugin loading, compilation, and execution.

## Namespace
[Styx.Plugins](../../../namespaces/Styx/Plugins.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class PluginManager
```

The PluginManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [IsBuildingPlugins](PluginManager/Properties/IsBuildingPlugins_BA3A2F226E33.md) | Gets whether plugins are currently being built/compiled. |
| Public property Static member | [IsInitialized](PluginManager/Properties/IsInitialized_5109DB3B9DB1.md) | Gets whether the plugin system is initialized. |
| Public property Static member | [Plugins](PluginManager/Properties/Plugins_572B3C914A98.md) | Gets all loaded plugins. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [CompileAndLoadFrom(string)](PluginManager/Methods/CompileAndLoadFrom_2861D8EB7847.md) | Compiles and loads plugins from a path. |
| Public method Static member | [Initialize(string[])](PluginManager/Methods/Initialize_08062985B647.md) | Initializes the plugin system. |
| Public method Static member | [RefreshPlugins(string[])](PluginManager/Methods/RefreshPlugins_87DFB19DB451.md) | Refreshes the plugin list by reloading from the Plugins directory. |
| Public method Static member | [SaveEnabledPlugins](PluginManager/Methods/SaveEnabledPlugins_FB6ECA5C43FE.md) | Saves the list of enabled plugins to CharacterSettings (legacy compatibility). |
| Public method Static member | [UpdateEnabledPlugins](PluginManager/Methods/UpdateEnabledPlugins_D0ADBFA8FD56.md) | Updates the EnabledPlugins property in CharacterSettings. Note: Does NOT save immediately - save is done at app close or bot start/stop (HB 4.3.4 pattern). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Plugins Namespace](../../../namespaces/Styx/Plugins.md)
