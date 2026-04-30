# EncryptedAttribute Class

Attribute for encrypting settings. Ported from HB 4.3.4 (RijndaelManaged → Aes for .NET 10).

## Inheritance Hierarchy
System.Object
  System.Attribute
    Styx.Helpers.SettingAttribute
      Styx.Helpers.EncryptedAttribute

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class EncryptedAttribute : SettingAttribute
```

The EncryptedAttribute type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [EncryptedAttribute(string, string)](EncryptedAttribute/Constructors/Constructor_750224C4568C.md) | Initializes a new instance of the EncryptedAttribute class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | TypeId | Gets the type id. (Inherited from Attribute.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Decrypt(byte[])](EncryptedAttribute/Methods/Decrypt_59E2F6341EC8.md) | Decrypts the value. |
| Public method | [Encrypt(string)](EncryptedAttribute/Methods/Encrypt_BAC8EC3BEB89.md) | Encrypts the value. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from Attribute.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from Attribute.) |
| Public method | IsDefaultAttribute | Determines whether is default attribute. (Inherited from Attribute.) |
| Public method | Match(object) | Determines whether the attribute matches the specified object. (Inherited from Attribute.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
