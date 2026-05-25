# CompileBatch Class

Batches C# expression strings from quest behaviors and compiles them together into a single assembly whose class inherits ProfileHelperFunctionsBase. Ported from HB 6.2.3 Styx.CommonBot.Profiles.Quest.Order.CompileBatch, using Roslyn instead of CodeDom.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.CompileBatch

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class CompileBatch
```

The CompileBatch type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [CompileBatch](CompileBatch/Constructors/Constructor_7C51B7118EFD.md) | Initializes a new instance of the CompileBatch class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Errors](CompileBatch/Properties/Errors_D9D7E42605D2.md) | Gets the errors. |
| Public property | [HasErrors](CompileBatch/Properties/HasErrors_5E8E4EA0A0E1.md) | Gets a value indicating whether has errors. |
| Public property | [HasPendingExpressions](CompileBatch/Properties/HasPendingExpressions_ED252A047BAB.md) | Gets a value indicating whether has pending expressions. |
| Public property | [Imports](CompileBatch/Properties/Imports_B0855A9ED793.md) | Gets the imports. |
| Public property | [IsCompiled](CompileBatch/Properties/IsCompiled_FF2B1C470582.md) | Gets a value indicating whether is compiled. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Add(string, object)](CompileBatch/Methods/Add_18E772690890.md) | Registers a raw code string (Type="Definition" from RunCode) as a class-body member. |
| Public method | [AddExpression(DelayCompiledExpression, object)](CompileBatch/Methods/AddExpression_AAB476186090.md) | Registers a DelayCompiledExpression with the batch. The expression's CompiledExpression field is populated after Compile() succeeds. |
| Public method | [AddImport(string)](CompileBatch/Methods/AddImport_4EE7595DE29C.md) | Adds the import. |
| Public method | [Compile](CompileBatch/Methods/Compile_7F61975BFB45.md) | Compiles all registered code and expressions into a single assembly. Sets CompiledExpression on each registered DelayCompiledExpression. |
| Public method | [GetDefinitionCode](CompileBatch/Methods/GetDefinitionCode_FFFFCBF479CB.md) | Returns all raw code strings registered via Add() (Type="Definition" entries). Used by ProfileBatchManager to carry definitions forward into new batches. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
