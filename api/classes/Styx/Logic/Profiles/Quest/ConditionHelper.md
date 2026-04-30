# ConditionHelper Class

Compiles and evaluates C# condition expressions at runtime. Implements same pattern as HB 6.2.3 ConditionHelper with: - Fast-path parser for common expressions (Class, Race, Level, HasQuest, IsQuestCompleted) - Roslyn fallback for complex expressions - Expression caching to prevent memory issues

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.ConditionHelper

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ConditionHelper
```

The ConditionHelper type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ConditionHelper(string)](ConditionHelper/Constructors/Constructor_17611D8C28FE.md) | Initializes a new instance of the ConditionHelper class. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CompileAndBindExpression(string[], Func<bool>)](ConditionHelper/Methods/CompileAndBindExpression_799FEA39E8EA.md) | Compile expression and return bound delegate using Roslyn |
| Public method Static member | [ParseConditionString(string)](ConditionHelper/Methods/ParseConditionString_CE7191E118BA.md) | Parses the condition string. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
