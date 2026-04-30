# DelayCompiledExpression Class

Holds a C# expression string whose delegate is compiled lazily by CompileBatch. The CallableExpression property is always callable but throws if Compile() has not been called. Ported from HB 6.2.3 Styx.CommonBot.Profiles.Quest.Order.DelayCompiledExpression.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Quest.DelayCompiledExpression

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class DelayCompiledExpression
```

The DelayCompiledExpression type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [DelayCompiledExpression(string, Type)](DelayCompiledExpression/Constructors/Constructor_7FB364CF1FDE.md) | Initializes a new instance of the DelayCompiledExpression class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CallableExpression](DelayCompiledExpression/Properties/CallableExpression_D54B728C046D.md) | Gets the callable expression. |
| Public property | [DelegateType](DelayCompiledExpression/Properties/DelegateType_ED1373D04988.md) | Gets the delegate type. |
| Public property | [ExpressionString](DelayCompiledExpression/Properties/ExpressionString_7E261C37054D.md) | Gets the expression string. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Condition(string)](DelayCompiledExpression/Methods/Condition_68E580F78CF8.md) | Creates a condition expression. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
