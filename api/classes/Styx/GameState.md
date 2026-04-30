# GameState Enumeration

Game state enumeration — matches HB 4.3.4 values. Read from memory at 0x00B6A9E0 (WotLK 3.3.5a). Note: ChangingFactionOrRace exists in WotLK (Faction Change 3.2.0, Race Change 3.3.3). ScanDllScanning is the Warden anti-cheat scan state.

## Namespace
[Styx](../../namespaces/Styx.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum GameState
```

The GameState type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GameState](GameState/Constructors/Constructor_095BF5EA3349.md) | Initializes a new instance of the GameState enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [ChangingFactionOrRace](GameState/Fields/ChangingFactionOrRace_921885B26545.md) | Represents the changing faction or race value. |
| Public field | [ChangingRealm](GameState/Fields/ChangingRealm_F6908A32E173.md) | Represents the changing realm value. |
| Public field | [CharacterDecline](GameState/Fields/CharacterDecline_FEAA8AB978CA.md) | Represents the character decline value. |
| Public field | [CharacterRename](GameState/Fields/CharacterRename_68403779C8EB.md) | Represents the character rename value. |
| Public field | [CreatingCharacter](GameState/Fields/CreatingCharacter_C886820BC64C.md) | Represents the creating character value. |
| Public field | [DeletingCharacter](GameState/Fields/DeletingCharacter_DDB84246B6C9.md) | Represents the deleting character value. |
| Public field | [Exiting](GameState/Fields/Exiting_70211281BF20.md) | Represents the exiting value. |
| Public field | [Idling](GameState/Fields/Idling_9708BC9848D1.md) | Represents the idling value. |
| Public field | [LoggingIn](GameState/Fields/LoggingIn_328717FDF5B8.md) | Represents the logging in value. |
| Public field | [NonPersonalInfoSurvey](GameState/Fields/NonPersonalInfoSurvey_216A6A81E91A.md) | Represents the non personal info survey value. |
| Public field | [QueryingRealmList](GameState/Fields/QueryingRealmList_0C00126787C6.md) | Represents the querying realm list value. |
| Public field | [ScanDllScanning](GameState/Fields/ScanDllScanning_C658710B562B.md) | Represents the scan dll scanning value. |
| Public field | [SelectingCharacter](GameState/Fields/SelectingCharacter_0FEBB93439EF.md) | Represents the selecting character value. |
| Public field | [Unknown](GameState/Fields/Unknown_3F261D23CF0F.md) | Represents the unknown value. |
| Public field | [Zoning](GameState/Fields/Zoning_891CD4665274.md) | Represents the zoning value. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | CompareTo(object) | Compares the current instance with another object. (Inherited from Enum.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().). (Inherited from Enum.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().). (Inherited from Enum.) |
| Public method | GetTypeCode | Gets the type code. (Inherited from Enum.) |
| Public method | HasFlag(Enum) | Determines whether has flag. (Inherited from Enum.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides ValueType.ToString().). (Inherited from Enum.) |
| Public method | ToString(string) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(string, IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx Namespace](../../namespaces/Styx.md)
