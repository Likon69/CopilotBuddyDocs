# WoWGlyphInfo Struct

FEAT-17: Glyph slot information for WotLK (6 slots: 3 major, 3 minor).

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct WoWGlyphInfo
```

The WoWGlyphInfo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWGlyphInfo](WoWGlyphInfo/Constructors/Constructor_AF2E151DCB35.md) | Initializes a new instance of the WoWGlyphInfo struct. |
| Public constructor | [WoWGlyphInfo(int, uint, uint, bool)](WoWGlyphInfo/Constructors/Constructor_0A242A8B2D34.md) | Initializes a new instance of the WoWGlyphInfo struct. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [GlyphId](WoWGlyphInfo/Properties/GlyphId_A41D385B4500.md) | Glyph spell ID (0 = empty slot). |
| Public property | [HasGlyph](WoWGlyphInfo/Properties/HasGlyph_FF7C6D70EAC0.md) | Whether this slot has a glyph socketed. |
| Public property | [IsEnabled](WoWGlyphInfo/Properties/IsEnabled_475962D8A994.md) | Whether this slot is enabled. |
| Public property | [Slot](WoWGlyphInfo/Properties/Slot_FC8165D7BD2E.md) | Slot index (0-5). |
| Public property | [SlotType](WoWGlyphInfo/Properties/SlotType_EE97E4EDBC93.md) | Glyph slot type ID (defines major/minor). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [ToString](WoWGlyphInfo/Methods/ToString_326C010FCEBF.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
