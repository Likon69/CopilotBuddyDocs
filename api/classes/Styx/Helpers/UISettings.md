# UISettings Class

Settings for UI window positions and sizes. Global (not per-character) — stored in Settings/UISettings.xml. Pattern from HB 5.4.8.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Styx.Helpers.UISettings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class UISettings : Settings
```

The UISettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [UISettings](UISettings/Constructors/Constructor_C0ADA091D412.md) | Initializes a new instance of the UISettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](UISettings/Fields/Instance_933919B48CE4.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [EnhancedMode](UISettings/Properties/EnhancedMode_632AFD0F74D2.md) | Gets or sets a value indicating whether enhanced mode. |
| Public property | [MainWindowHeight](UISettings/Properties/MainWindowHeight_373B8BF42A18.md) | Gets or sets the main window height. |
| Public property | [MainWindowLocationX](UISettings/Properties/MainWindowLocationX_526C7BC8F353.md) | Gets or sets the main window location x. |
| Public property | [MainWindowLocationY](UISettings/Properties/MainWindowLocationY_FDF197616657.md) | Gets or sets the main window location y. |
| Public property | [MainWindowState](UISettings/Properties/MainWindowState_000B56CBE0BD.md) | Gets or sets the main window state. |
| Public property | [MainWindowWidth](UISettings/Properties/MainWindowWidth_4FC4BD032BBA.md) | Gets or sets the main window width. |
| Public property | [SettingsWindowHeight](UISettings/Properties/SettingsWindowHeight_5BA9DEA752FD.md) | Gets or sets the settings window height. |
| Public property | [SettingsWindowLocationX](UISettings/Properties/SettingsWindowLocationX_C91F63A20E3B.md) | Gets or sets the settings window location x. |
| Public property | [SettingsWindowLocationY](UISettings/Properties/SettingsWindowLocationY_235EFA155651.md) | Gets or sets the settings window location y. |
| Public property | [SettingsWindowState](UISettings/Properties/SettingsWindowState_A4E49BB7B846.md) | Gets or sets the settings window state. |
| Public property | [SettingsWindowWidth](UISettings/Properties/SettingsWindowWidth_7EB442FCA0EE.md) | Gets or sets the settings window width. |
| Public property | [SettingsPath](Settings/Properties/SettingsPath_714F163EBCDE.md) | Gets the settings path. (Inherited from Settings.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetSettings](Settings/Methods/GetSettings_409D809C21FE.md) | Gets the settings. (Inherited from Settings.) |
| Public method | [GetXML](Settings/Methods/GetXML_668D906A4E6F.md) | Gets the xml. (Inherited from Settings.) |
| Public method | [InitializeDefaultValues](Settings/Methods/InitializeDefaultValues_ECF3519AB22C.md) | Initializes the default values. (Inherited from Settings.) |
| Public method | [Load](Settings/Methods/Load_0AA938C42077.md) | Loads settings from the current settings file. Pattern from HB 5.4.8: checks File.Exists and uses StreamReader. (Inherited from Settings.) |
| Public method | [LoadFromXML(XElement)](Settings/Methods/LoadFromXML_76C8E7C7C070.md) | Loads from xml. (Inherited from Settings.) |
| Public method | [Save](Settings/Methods/Save_BD2822350866.md) | Saves the current state. (Inherited from Settings.) |
| Public method | [SaveToFile(string)](Settings/Methods/SaveToFile_923F70D783F6.md) | Saves to file. (Inherited from Settings.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
