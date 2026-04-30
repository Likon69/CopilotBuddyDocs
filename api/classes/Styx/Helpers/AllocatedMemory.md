# AllocatedMemory Class

Manages allocated memory chunks in the WoW process. Port from HB 3.3.5a Styx.Helpers.AllocatedMemory

## Inheritance Hierarchy
System.Object
  Styx.Helpers.AllocatedMemory

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class AllocatedMemory : IDisposable
```

The AllocatedMemory type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AllocatedMemory(int)](AllocatedMemory/Constructors/Constructor_FDD92DE24A6D.md) | Initializes a new instance of the AllocatedMemory class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Address](AllocatedMemory/Properties/Address_9B4340E0366A.md) | Gets the address. |
| Public property | [this[string]](AllocatedMemory/Properties/Item_0DBEE577C46D.md) | Gets the address of a named allocated chunk. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AllocateOfChunk(string)](AllocatedMemory/Methods/AllocateOfChunk_DAAED2283DA7.md) | Allocates a chunk of memory for a type with a given name. |
| Public method | [AllocateOfChunk(string, int)](AllocatedMemory/Methods/AllocateOfChunk_4E29AB548E10.md) | Allocates a chunk of memory with a given name and size. |
| Public method | [Dispose](AllocatedMemory/Methods/Dispose_CF4043147789.md) | Releases the resources used by the instance. |
| Public method | [GetAddress(int)](AllocatedMemory/Methods/GetAddress_4970E06666CD.md) | Gets address at a specific byte offset. |
| Public method | [GetAllocatedChunk(string)](AllocatedMemory/Methods/GetAllocatedChunk_0DA716C8E1A8.md) | Gets the address of a named allocated chunk. |
| Public method | [Read(int)](AllocatedMemory/Methods/Read_12A9A4AEEEF8.md) | Reads a value at a specific byte offset. |
| Public method | [Read(string)](AllocatedMemory/Methods/Read_D606F8A6A1EE.md) | Reads a value from a named allocated chunk. |
| Public method | [Write(int, T)](AllocatedMemory/Methods/Write_241349A68F67.md) | Writes a value at a specific byte offset. |
| Public method | [Write(string, T)](AllocatedMemory/Methods/Write_ED6CEA9E62C5.md) | Writes a value to a named allocated chunk. |
| Public method | [Write(string, int, T)](AllocatedMemory/Methods/Write_63004E374C0E.md) | Writes a value to a named allocated chunk at a specific offset. |
| Public method | [WriteByte(int, byte)](AllocatedMemory/Methods/WriteByte_D95364FC33D9.md) | Writes a single byte at a specific byte offset. |
| Public method | [WriteBytes(int, byte[])](AllocatedMemory/Methods/WriteBytes_8474D296E000.md) | Writes bytes at a specific byte offset. |
| Public method | [WriteBytes(string, byte[])](AllocatedMemory/Methods/WriteBytes_6BBACFB846EE.md) | Writes bytes to a named allocated chunk. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
