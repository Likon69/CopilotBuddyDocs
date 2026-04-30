# PVPSettings Class

PVP/Battleground settings. Path: Settings/PVPSettings_{Name}.xml Pattern from HB 3.3.5a.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Styx.Helpers.PVPSettings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PVPSettings : Settings
```

The PVPSettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PVPSettings](PVPSettings/Constructors/Constructor_C767B50AE9C1.md) | Initializes a new instance of the PVPSettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](PVPSettings/Fields/Instance_3D4FD9D5251A.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BG1](PVPSettings/Properties/BG1_C259A47CC69A.md) | First battleground to queue for. |
| Public property | [BG2](PVPSettings/Properties/BG2_9A833C5988A9.md) | Second battleground to queue for. |
| Public property | [BG3](PVPSettings/Properties/BG3_D87B5DD97444.md) | Third battleground to queue for. |
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
