# IHBPlugin Interface

Interface for CopilotBuddy plugins.

## Namespace
[Styx.Plugins.PluginClass](../../../../namespaces/Styx/Plugins/PluginClass.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public interface IHBPlugin : IDisposable, IEquatable<IHBPlugin>
```

The IHBPlugin type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Author](IHBPlugin/Properties/Author_6D69D2F80094.md) | Gets the name of the plugin author. |
| Public property | [ButtonText](IHBPlugin/Properties/ButtonText_8662D7EA64CE.md) | Gets the text displayed on the plugin's UI button. |
| Public property | [Name](IHBPlugin/Properties/Name_3BDFF5C74BBB.md) | Gets the name of the plugin. |
| Public property | [Version](IHBPlugin/Properties/Version_1DFACE0AEF97.md) | Gets the version of the plugin. |
| Public property | [WantButton](IHBPlugin/Properties/WantButton_721779946107.md) | Gets a value indicating whether the plugin wants a UI button. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Initialize](IHBPlugin/Methods/Initialize_82E9F86AA58F.md) | Called once when the plugin is first loaded. |
| Public method | [OnButtonPress](IHBPlugin/Methods/OnButtonPress_D4A37482380B.md) | Called when the user clicks the plugin's UI button. Only called if WantButton is true. |
| Public method | [Pulse](IHBPlugin/Methods/Pulse_B9A6B91CDB17.md) | Called every frame while the plugin is active. |
| Public method | Dispose | Releases the resources used by the instance. (Inherited from IDisposable.) |
| Public method | Equals(IHBPlugin) | Determines whether the specified object is equal to the current object. (Inherited from IEquatable<IHBPlugin>.) |

## See Also
[Styx.Plugins.PluginClass Namespace](../../../../namespaces/Styx/Plugins/PluginClass.md)
