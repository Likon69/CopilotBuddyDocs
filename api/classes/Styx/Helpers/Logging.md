# Logging Class

Logging system compatible with Honorbuddy WoD style.

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Logging
```

The Logging type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public delegate | [Logging.LogMessageDelegate](Logging/LogMessageDelegate.md) | Delegate for log message events. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [ColorDiagnostic](Logging/Fields/ColorDiagnostic_15A6ECC0DFF0.md) | Represents the color diagnostic. |
| Public field Static member | [ColorError](Logging/Fields/ColorError_40EF12B29FED.md) | Represents the color error. |
| Public field Static member | [ColorNormal](Logging/Fields/ColorNormal_A5D417EC29DB.md) | Represents the color normal. |
| Public field Static member | [ColorQuiet](Logging/Fields/ColorQuiet_ACAD6B5FE635.md) | Represents the color quiet. |
| Public field Static member | [ColorVerbose](Logging/Fields/ColorVerbose_CDF2FAFD1146.md) | Represents the color verbose. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [ApplicationPath](Logging/Properties/ApplicationPath_390307F5615E.md) | Gets the application startup path. |
| Public property Static member | [FileLogging](Logging/Properties/FileLogging_0C7B4DF84B62.md) | Gets or sets whether file logging is enabled. |
| Public property Static member | [LogFileLevel](Logging/Properties/LogFileLevel_8C008977CBE5.md) | Gets or sets the logging level for file output. |
| Public property Static member | [LogFilePath](Logging/Properties/LogFilePath_06D51ECA55F4.md) | Gets or sets the log file path. |
| Public property Static member | [LoggingLevel](Logging/Properties/LoggingLevel_D5918F334AF3.md) | Gets or sets the current logging level for UI display. |
| Public property Static member | [StartTime](Logging/Properties/StartTime_A850EC44C077.md) | Gets the startup time. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnLogMessage](Logging/Events/OnLogMessage_E16B1BCDFBEB.md) | Event fired when log messages are written. |
| Public event Static member | [OnMessageLogged](Logging/Events/OnMessageLogged_BAA511C7E447.md) | Occurs when message logged. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FileOnly(string)](Logging/Methods/FileOnly_04D0837A0C5B.md) | Writes a message to the log file only, without displaying it in the UI. Ported from HB 4.3.4 Logging.FileOnly. |
| Public method Static member | [FileOnly(string, object[])](Logging/Methods/FileOnly_7F1E17A40F43.md) | Writes a formatted message to the log file only, without displaying it in the UI. Ported from HB 4.3.4 Logging.FileOnly. |
| Public method Static member | [Write(string)](Logging/Methods/Write_CA0402B113EC.md) | Writes the value. |
| Public method Static member | [Write(LogLevel, string)](Logging/Methods/Write_B5933E6C1BEB.md) | Writes the value. |
| Public method Static member | [Write(Color, string)](Logging/Methods/Write_AFEAB1F0E6E0.md) | Writes the value. |
| Public method Static member | [Write(string, object[])](Logging/Methods/Write_64C8032A242F.md) | Writes the value. |
| Public method Static member | [Write(Color, string)](Logging/Methods/Write_E1AE20AEC5DB.md) | Writes the value. |
| Public method Static member | [Write(LogLevel, Color, string)](Logging/Methods/Write_D14E2C1F79B1.md) | Writes the value. |
| Public method Static member | [Write(LogLevel, string, object[])](Logging/Methods/Write_ECF97D0AE9C8.md) | Writes the value. |
| Public method Static member | [Write(Color, string, object[])](Logging/Methods/Write_4BABFBC3857C.md) | Writes the value. |
| Public method Static member | [Write(Color, string, object[])](Logging/Methods/Write_1E2CAF26875F.md) | Writes the value. |
| Public method Static member | [Write(LogLevel, Color, string, object[])](Logging/Methods/Write_E11B82F7B9AA.md) | Writes the value. |
| Public method Static member | [WriteCombat(string)](Logging/Methods/WriteCombat_DCD23494D997.md) | Writes the combat. |
| Public method Static member | [WriteDebug(string)](Logging/Methods/WriteDebug_F26C8A93C696.md) | Writes the debug. |
| Public method Static member | [WriteDebug(string, object[])](Logging/Methods/WriteDebug_0EA7699A9634.md) | Writes the debug. |
| Public method Static member | [WriteDebug(Color, string)](Logging/Methods/WriteDebug_CB911127BFDA.md) | Writes the debug. |
| Public method Static member | [WriteDebug(Color, string, object[])](Logging/Methods/WriteDebug_AC0DBFA4A678.md) | Writes the debug. |
| Public method Static member | [WriteDiagnostic(string)](Logging/Methods/WriteDiagnostic_6F5D28147719.md) | Writes a diagnostic message. |
| Public method Static member | [WriteDiagnostic(Color, string)](Logging/Methods/WriteDiagnostic_3AAD211DAF1E.md) | Writes a diagnostic message. |
| Public method Static member | [WriteDiagnostic(string, object[])](Logging/Methods/WriteDiagnostic_F56660D140D5.md) | Writes a diagnostic message. |
| Public method Static member | [WriteDiagnostic(Color, string, object[])](Logging/Methods/WriteDiagnostic_2A767669EDB4.md) | Writes a diagnostic message. |
| Public method Static member | [WriteError(string)](Logging/Methods/WriteError_CBD8C3A7CAEF.md) | Writes an error entry. |
| Public method Static member | [WriteException(Exception)](Logging/Methods/WriteException_2239377CE925.md) | Writes the exception. |
| Public method Static member | [WriteException(LogLevel, Exception)](Logging/Methods/WriteException_43310F0C583F.md) | Writes the exception. |
| Public method Static member | [WriteException(Color, Exception)](Logging/Methods/WriteException_73FE662C604E.md) | Writes the exception. |
| Public method Static member | [WriteException(LogLevel, Color, Exception)](Logging/Methods/WriteException_7F9207CA8EBD.md) | Writes the exception. |
| Public method Static member | [WriteNavigator(string)](Logging/Methods/WriteNavigator_22CE879840C2.md) | Writes the navigator. |
| Public method Static member | [WriteNavigator(string, object[])](Logging/Methods/WriteNavigator_4706C923AEC5.md) | Writes the navigator. |
| Public method Static member | [WriteNavigator(Color, string)](Logging/Methods/WriteNavigator_66FB50F10798.md) | Writes the navigator. |
| Public method Static member | [WriteNavigator(Color, string, object[])](Logging/Methods/WriteNavigator_8CCEC04C2FFA.md) | Writes the navigator. |
| Public method Static member | [WriteQuiet(string)](Logging/Methods/WriteQuiet_4B7A343A6878.md) | Writes the quiet. |
| Public method Static member | [WriteQuiet(Color, string)](Logging/Methods/WriteQuiet_7822364553F8.md) | Writes the quiet. |
| Public method Static member | [WriteQuiet(string, object[])](Logging/Methods/WriteQuiet_2A0EBBE49623.md) | Writes the quiet. |
| Public method Static member | [WriteQuiet(Color, string, object[])](Logging/Methods/WriteQuiet_53F404A0A0F2.md) | Writes the quiet. |
| Public method Static member | [WriteToFileSync(LogLevel, string)](Logging/Methods/WriteToFileSync_20B040C72E9D.md) | Writes the to file sync. |
| Public method Static member | [WriteToFileSync(LogLevel, string, object[])](Logging/Methods/WriteToFileSync_2E3C7C8C0F44.md) | Writes the to file sync. |
| Public method Static member | [WriteVerbose(string)](Logging/Methods/WriteVerbose_282151D0B506.md) | Writes the verbose. |
| Public method Static member | [WriteVerbose(Color, string)](Logging/Methods/WriteVerbose_6E49439F4D1A.md) | Writes the verbose. |
| Public method Static member | [WriteVerbose(string, object[])](Logging/Methods/WriteVerbose_511855EF52D2.md) | Writes the verbose. |
| Public method Static member | [WriteVerbose(Color, string, object[])](Logging/Methods/WriteVerbose_EBEB8CD06290.md) | Writes the verbose. |
| Public method Static member | [WriteWarning(string)](Logging/Methods/WriteWarning_DF72F9C5489C.md) | Writes the warning. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
