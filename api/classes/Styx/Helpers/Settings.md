# Settings Class

Base class for all settings. Ported from HB 3.3.5a Settings.cs. Per-character settings use flat path: Settings/FileName_{Name}.xml Supports migration from old paths via oldSettingsPath parameter.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class Settings
```

The Settings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [Settings(string, string)](Settings/Constructors/Constructor_5EF5A6333F8D.md) | Constructor matching HB 5.4.8 pattern. Supports migration from an old settings path to a new one. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [SettingsDirectory](Settings/Properties/SettingsDirectory_33FF50E1BF1D.md) | Root settings directory: {AppPath}/Settings/ Pattern from HB 5.4.8. |
| Public property | [SettingsPath](Settings/Properties/SettingsPath_714F163EBCDE.md) | Gets the settings path. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetSettings](Settings/Methods/GetSettings_409D809C21FE.md) | Gets the settings. |
| Public method | [GetXML](Settings/Methods/GetXML_668D906A4E6F.md) | Gets the xml. |
| Public method | [InitializeDefaultValues](Settings/Methods/InitializeDefaultValues_ECF3519AB22C.md) | Initializes the default values. |
| Public method | [Load](Settings/Methods/Load_0AA938C42077.md) | Loads settings from the current settings file. Pattern from HB 5.4.8: checks File.Exists and uses StreamReader. |
| Public method Static member | [LoadFromFile(string)](Settings/Methods/LoadFromFile_1B36DA2733F3.md) | Loads from file. |
| Public method | [LoadFromXML(XElement)](Settings/Methods/LoadFromXML_76C8E7C7C070.md) | Loads from xml. |
| Public method Static member | [LoadFromXML(XElement)](Settings/Methods/LoadFromXML_ECDD26BE88A7.md) | Loads from xml. |
| Public method | [Save](Settings/Methods/Save_BD2822350866.md) | Saves the current state. |
| Public method | [SaveToFile(string)](Settings/Methods/SaveToFile_923F70D783F6.md) | Saves to file. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
