# CustomForcedBehavior Class

Represents a custom forced behavior.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Questing.CustomForcedBehavior

## Namespace
[Styx.Logic.Questing](../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class CustomForcedBehavior
```

The CustomForcedBehavior type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [CustomForcedBehavior.ConfigMemento](CustomForcedBehavior/ConfigMemento.md) | Represents a config memento. |
| Public class | [CustomForcedBehavior.ConstrainAs](CustomForcedBehavior/ConstrainAs.md) | Represents a constrain as. |
| Public class | [CustomForcedBehavior.ConstrainTo](CustomForcedBehavior/ConstrainTo.md) | Represents a constrain to. |
| Public class | [CustomForcedBehavior.IConstraintChecker<T>](CustomForcedBehavior/IConstraintChecker_1.md) | Represents an i constraint checker. |
| Public enumeration | [CustomForcedBehavior.QuestCompleteRequirement](CustomForcedBehavior/QuestCompleteRequirement.md) | Represents values for Quest Complete Requirement. |
| Public enumeration | [CustomForcedBehavior.QuestInLogRequirement](CustomForcedBehavior/QuestInLogRequirement.md) | Represents values for Quest In Log Requirement. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [CustomForcedBehavior(Dictionary<string, string>)](CustomForcedBehavior/Constructors/Constructor_3D157493982E.md) | Initializes a new instance of the CustomForcedBehavior class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Args](CustomForcedBehavior/Properties/Args_33815513A17F.md) | Gets the args. |
| Public property | [Branch](CustomForcedBehavior/Properties/Branch_0A25844B8892.md) | Gets the branch. |
| Public property | [Element](CustomForcedBehavior/Properties/Element_F6ADCA284FB6.md) | Gets or sets the element. |
| Public property | [IsAttributeProblem](CustomForcedBehavior/Properties/IsAttributeProblem_0BCD13613131.md) | Gets or sets a value indicating whether is attribute problem. |
| Public property | [IsDone](CustomForcedBehavior/Properties/IsDone_91DB27A07CC9.md) | Gets a value indicating whether is done. |
| Public property | [SubversionId](CustomForcedBehavior/Properties/SubversionId_015A5B4C5762.md) | Gets the subversion id. |
| Public property | [SubversionRevision](CustomForcedBehavior/Properties/SubversionRevision_EEC6CBB6D26B.md) | Gets the subversion revision. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CheckForUnrecognizedAttributes(Dictionary<string, object>)](CustomForcedBehavior/Methods/CheckForUnrecognizedAttributes_E5C2DE9BC51D.md) | Checks for unrecognized attributes. |
| Protected method | [CreateBehavior](CustomForcedBehavior/Methods/CreateBehavior_7E7A0430C5B0.md) | Creates the behavior. |
| Public method | [Dispose](CustomForcedBehavior/Methods/Dispose_4A68D8202143.md) | Releases the resources used by the instance. |
| Protected method | [Execute](CustomForcedBehavior/Methods/Execute_E99D5B0FDA0C.md) | Executes the operation. |
| Public method | [GetAttributeAs(string, bool, IConstraintChecker<T>, string[])](CustomForcedBehavior/Methods/GetAttributeAs_EECAF1ABE701.md) | Gets the attribute as. |
| Public method | [GetAttributeAsArray(string, bool, IConstraintChecker<T>, string[], char[])](CustomForcedBehavior/Methods/GetAttributeAsArray_ADE035F6CEA1.md) | Gets the attribute as array. |
| Public method | [GetAttributeAsBoolean(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsBoolean_2D7A2041ECEB.md) | Gets the attribute as boolean. |
| Public method | [GetAttributeAsBoolean(string, bool, string, bool)](CustomForcedBehavior/Methods/GetAttributeAsBoolean_327A6589A0FD.md) | Gets the attribute as boolean. |
| Public method | [GetAttributeAsColor(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsColor_84D456D196B3.md) | Gets the attribute as color. |
| Public method | [GetAttributeAsDouble(string, bool, double, double, string[])](CustomForcedBehavior/Methods/GetAttributeAsDouble_AC6ED1FF3BA0.md) | Gets the attribute as double. |
| Public method | [GetAttributeAsDoubleArray(string, bool, double, double, string[])](CustomForcedBehavior/Methods/GetAttributeAsDoubleArray_51A03DE37DB4.md) | Gets the attribute as double array. |
| Public method | [GetAttributeAsEnum(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsEnum_6E5C0D006440.md) | Gets the attribute as enum. |
| Public method | [GetAttributeAsEnum(string, bool, T, T)](CustomForcedBehavior/Methods/GetAttributeAsEnum_7C40DA24530F.md) | Gets the attribute as enum. |
| Public method | [GetAttributeAsFactionId(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsFactionId_DA4AC817AD19.md) | Gets the attribute as faction id. |
| Public method | [GetAttributeAsFloat(string, bool, string, float, float, float)](CustomForcedBehavior/Methods/GetAttributeAsFloat_3DAF5D352E75.md) | Gets the attribute as float. |
| Public method | [GetAttributeAsHotbarButton(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsHotbarButton_80927A62C265.md) | Gets the attribute as hotbar button. |
| Public method | [GetAttributeAsInteger(string, bool, int, int, string[])](CustomForcedBehavior/Methods/GetAttributeAsInteger_ADF198AE5C69.md) | Gets the attribute as integer. |
| Public method | [GetAttributeAsInteger(string, bool, string, int, int, int)](CustomForcedBehavior/Methods/GetAttributeAsInteger_4E1645722B62.md) | Gets the attribute as integer. |
| Public method | [GetAttributeAsIntegerArray(string, bool, int, int, string[])](CustomForcedBehavior/Methods/GetAttributeAsIntegerArray_A5776EB50151.md) | Gets the attribute as integer array. |
| Public method | [GetAttributeAsItemId(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsItemId_2C4C0105EBF1.md) | Gets the attribute as item id. |
| Public method | [GetAttributeAsMobId(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsMobId_AE46C7711F8D.md) | Gets the attribute as mob id. |
| Public method | [GetAttributeAsNullable(string, bool, IConstraintChecker<T>, string[])](CustomForcedBehavior/Methods/GetAttributeAsNullable_1B708BC83579.md) | Gets the attribute as nullable. |
| Public method | [GetAttributeAsNumOfTimes(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsNumOfTimes_CEFAE0F6535F.md) | Gets the attribute as num of times. |
| Public method | [GetAttributeAsQuestId(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsQuestId_B204C13D8B31.md) | Gets the attribute as quest id. |
| Public method | [GetAttributeAsRange(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsRange_E137186E05A7.md) | Gets the attribute as range. |
| Public method | [GetAttributeAsSpecificString(string, bool, string, Dictionary<string, object>, string)](CustomForcedBehavior/Methods/GetAttributeAsSpecificString_9FABF6547EC5.md) | Gets the attribute as specific string. |
| Public method | [GetAttributeAsSpellId(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsSpellId_7E91FEA784C2.md) | Gets the attribute as spell id. |
| Public method | [GetAttributeAsString(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsString_A9C85DCCB042.md) | Gets the attribute as string. |
| Public method | [GetAttributeAsString(string, bool, string, string)](CustomForcedBehavior/Methods/GetAttributeAsString_BA02E1E2B402.md) | Gets the attribute as string. |
| Public method | [GetAttributeAsString_NonEmpty(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsString_NonEmpty_22951423B56D.md) | Gets the attribute as string non empty. |
| Public method | [GetAttributeAsString_SpecificValue(string, bool, string[], string[])](CustomForcedBehavior/Methods/GetAttributeAsString_SpecificValue_598BFF028BDB.md) | Gets the attribute as string specific value. |
| Public method | [GetAttributeAsWaitTime(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsWaitTime_27D5429A20E2.md) | Gets the attribute as wait time. |
| Public method | [GetAttributeAsWoWPoints(string, bool, string[])](CustomForcedBehavior/Methods/GetAttributeAsWoWPoints_567DE415D19F.md) | Gets the attribute as wow points. |
| Public method | [GetNumberedAttributesAsArray(string, int, IConstraintChecker<T>, string[])](CustomForcedBehavior/Methods/GetNumberedAttributesAsArray_F8B48F8E044B.md) | Gets the numbered attributes as array. |
| Public method | [GetNumberedAttributesAsIntegerArray(string, int, int, int, string[])](CustomForcedBehavior/Methods/GetNumberedAttributesAsIntegerArray_52BE6FEE53CF.md) | Gets the numbered attributes as integer array. |
| Public method | [GetXYZAttributeAsWoWPoint(string, bool, string[])](CustomForcedBehavior/Methods/GetXYZAttributeAsWoWPoint_1937BA0DAC69.md) | Gets the xyz attribute as wow point. |
| Public method | [GetXYZAttributeAsWoWPoint(bool, WoWPoint, WoWPoint)](CustomForcedBehavior/Methods/GetXYZAttributeAsWoWPoint_B9F786A723B3.md) | Gets the xyz attribute as wow point. |
| Public method | [GetXYZAttributeAsWoWPoint(string, string, string, bool, WoWPoint, WoWPoint)](CustomForcedBehavior/Methods/GetXYZAttributeAsWoWPoint_9583E12DCA17.md) | Gets the xyz attribute as wow point. |
| Public method | [LegacyGetAttributeAsWoWPoint(string, bool, string[], string)](CustomForcedBehavior/Methods/LegacyGetAttributeAsWoWPoint_A892F6F51FB8.md) | Gets the attribute as a WoWPoint using the legacy parser. |
| Public method | [LogMessage(string, string, object[])](CustomForcedBehavior/Methods/LogMessage_103169B303CF.md) | Writes a log message. |
| Public method | [LogMessage(string, Color?, string, object[])](CustomForcedBehavior/Methods/LogMessage_65F67AA244A5.md) | Writes a log message. |
| Public method | [OnStart](CustomForcedBehavior/Methods/OnStart_2173A8850D56.md) | Handles the on start operation. |
| Public method | [OnStart_HandleAttributeProblem](CustomForcedBehavior/Methods/OnStart_HandleAttributeProblem_26E745C97CC3.md) | Handles the on start handle attribute problem operation. |
| Public method | [OnTick](CustomForcedBehavior/Methods/OnTick_B44746F65B3D.md) | Handles the on tick operation. |
| Public method | [UtilIsProgressRequirementsMet(int, QuestInLogRequirement, QuestCompleteRequirement)](CustomForcedBehavior/Methods/UtilIsProgressRequirementsMet_20A4D08EAC4F.md) | Determines whether the progress requirements are met. |
| Public method | [UtilLogMessage(string, string, object[])](CustomForcedBehavior/Methods/UtilLogMessage_FECEAD8222B7.md) | Writes a log message. |
| Public method | [UtilLogMessage(string, Color?, string, object[])](CustomForcedBehavior/Methods/UtilLogMessage_722558CB578D.md) | Writes a log message. |
| Protected method | [UtilReportMalformed(string, string)](CustomForcedBehavior/Methods/UtilReportMalformed_F899353DE840.md) | Reports a malformed value. |
| Protected method | [UtilReportValueFail(string, string, string)](CustomForcedBehavior/Methods/UtilReportValueFail_F6FB778F0CBE.md) | Reports a value validation failure. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Questing Namespace](../../../../namespaces/Styx/Logic/Questing.md)
