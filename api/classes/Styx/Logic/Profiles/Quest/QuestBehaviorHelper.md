# QuestBehaviorHelper Class

Compiles Quest Behaviors from C# source files at runtime using Roslyn. Quest Behaviors are placed in the "Quest Behaviors" folder next to the executable. Supports both single .cs files and folders containing multiple .cs files. Usage in profile XML:

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.QuestBehaviorHelper

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class QuestBehaviorHelper
```

The QuestBehaviorHelper type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestBehaviorHelper(string)](QuestBehaviorHelper/Constructors/Constructor_82BDC601CF49.md) | Creates a new QuestBehaviorHelper for the specified path. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Path](QuestBehaviorHelper/Properties/Path_30D014BA4CB8.md) | Path to the Quest Behavior source file or folder. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [ClearCache](QuestBehaviorHelper/Methods/ClearCache_ECB4EB5C4662.md) | Clears the assembly cache, forcing recompilation of all behaviors. Useful for development/debugging. |
| Public method | [GetAssembly](QuestBehaviorHelper/Methods/GetAssembly_07D14FC1C73C.md) | Gets the compiled assembly, compiling if necessary. |
| Public method Static member | [GetAssemblyCompiler(string)](QuestBehaviorHelper/Methods/GetAssemblyCompiler_D3CC02ACDCB3.md) | Creates a function that returns the compiled assembly for the specified behavior. This is the main entry point used by CodeNode.FromXml(). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
