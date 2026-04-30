# TileIdentifier Struct

Represents a navigation tile identifier.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct TileIdentifier : IEquatable<TileIdentifier>
```

The TileIdentifier type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [TileIdentifier](TileIdentifier/Constructors/Constructor_3D51FAA73CB7.md) | Initializes a new instance of the TileIdentifier struct. |
| Public constructor | [TileIdentifier(int, int)](TileIdentifier/Constructors/Constructor_EB1FD1E65E2F.md) | Initializes a new tile identifier with the specified coordinates. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [X](TileIdentifier/Properties/X_A8A1BBE31E3E.md) | Tile X coordinate (0-63 for standard WoW maps). |
| Public property | [Y](TileIdentifier/Properties/Y_0DAFC7F60298.md) | Tile Y coordinate (0-63 for standard WoW maps). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(TileIdentifier)](TileIdentifier/Methods/Equals_BB4CD76B161E.md) | Checks equality between two tile identifiers. |
| Public method | [Equals(object)](TileIdentifier/Methods/Equals_761C432D9B86.md) | Checks equality with another object. (Overrides ValueType.Equals().) |
| Public method Static member | [GetByPosition(float, float)](TileIdentifier/Methods/GetByPosition_66BA33F3C274.md) | Gets the tile identifier for a given world position. Coordinates: TileX = 32 - Floor(worldY / 533.3333), TileY = 32 - Floor(worldX / 533.3333) |
| Public method | [GetHashCode](TileIdentifier/Methods/GetHashCode_354FE9828CC6.md) | Gets the hash code for this tile identifier. (Overrides ValueType.GetHashCode().) |
| Public method | [ToString](TileIdentifier/Methods/ToString_0F481631565F.md) | Returns a string representation of this tile identifier. (Overrides ValueType.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
