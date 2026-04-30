# BGBotSettings Class

Represents settings for bg bot.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Styx.Helpers.BGBotSettings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class BGBotSettings : Settings
```

The BGBotSettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [BGBotSettings](BGBotSettings/Constructors/Constructor_8E09DD63612C.md) | Initializes a new instance of the BGBotSettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](BGBotSettings/Fields/Instance_87492C4A0AF1.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BG1](BGBotSettings/Properties/BG1_55B708B77D1C.md) | Gets or sets the bg1. |
| Public property | [BG2](BGBotSettings/Properties/BG2_F1F04D39F207.md) | Gets or sets the bg2. |
| Public property | [IncludeMountedPlayers](BGBotSettings/Properties/IncludeMountedPlayers_DED2E7BBF8E6.md) | Gets or sets a value indicating whether include mounted players. |
| Public property | [IsHealer](BGBotSettings/Properties/IsHealer_82E43B864ED8.md) | Gets or sets a value indicating whether is healer. |
| Public property | SettingsPath | Gets the settings path. (Inherited from Settings.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | GetSettings | Gets the settings. (Inherited from Settings.) |
| Public method | GetXML | Gets the xml. (Inherited from Settings.) |
| Public method | InitializeDefaultValues | Initializes the default values. (Inherited from Settings.) |
| Public method | Load | Loads settings from the current settings file. Pattern from HB 5.4.8: checks File.Exists and uses StreamReader. (Inherited from Settings.) |
| Public method | LoadFromXML(XElement) | Loads from xml. (Inherited from Settings.) |
| Public method | Save | Saves the current state. (Inherited from Settings.) |
| Public method | SaveToFile(string) | Saves to file. (Inherited from Settings.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
