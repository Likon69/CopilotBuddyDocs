# StyxSettings Class

Global bot settings (not per-character). Stored in Settings/StyxSettings.xml. Pattern from HB 5.4.8 GlobalSettings.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Styx.Helpers.StyxSettings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class StyxSettings : Settings
```

The StyxSettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [StyxSettings](StyxSettings/Constructors/Constructor_1685C050303B.md) | Initializes a new instance of the StyxSettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](StyxSettings/Fields/Instance_86F45B99BD0C.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [EnabledPlugins](StyxSettings/Properties/EnabledPlugins_32DF570848D3.md) | List of enabled plugins. |
| Public property | [FormLocationX](StyxSettings/Properties/FormLocationX_479598FC901D.md) | Form X location. |
| Public property | [FormLocationY](StyxSettings/Properties/FormLocationY_1B0983133E3A.md) | Form Y location. |
| Public property | [KillBetweenHotspots](StyxSettings/Properties/KillBetweenHotspots_D2A63A5F7F28.md) | Kill mobs between hotspots. |
| Public property | [LoggingLevel](StyxSettings/Properties/LoggingLevel_1ABE67E58EF7.md) | Log level for UI display. Matches HB WoD: None, Quiet, Normal, Verbose, Diagnostic. |
| Public property | [LogoutForInactivity](StyxSettings/Properties/LogoutForInactivity_ED3A33EFD4ED.md) | Log out after detecting inactivity. |
| Public property | [LogoutInactivityTimer](StyxSettings/Properties/LogoutInactivityTimer_2A7AB92268B6.md) | Minutes of inactivity before logout. |
| Public property | [LogoutInactivityUseForceQuit](StyxSettings/Properties/LogoutInactivityUseForceQuit_328982BDC731.md) | Use force quit when logging out for inactivity. |
| Public property | [MeshesFolderPath](StyxSettings/Properties/MeshesFolderPath_BBF4680BF71E.md) | Path to meshes folder. |
| Public property | [ProfileDebuggingMode](StyxSettings/Properties/ProfileDebuggingMode_17D30BE49DB0.md) | Enable profile debugging mode for verbose logging. |
| Public property | [UseExperimentalPathFollowing](StyxSettings/Properties/UseExperimentalPathFollowing_C2D459D0CB66.md) | Use experimental path following. |
| Public property | [UseFrameLock](StyxSettings/Properties/UseFrameLock_A74DDFE277C0.md) | Whether to use the memory frame lock during bot ticks. When enabled (HB 5.4.8/6.2.3 default), the entire tick runs inside a hard AcquireFrame — all game reads are consistent within one frame. |
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
